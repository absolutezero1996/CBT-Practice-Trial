## Questionnaire sets

This build has two complete questionnaire selections:

- **Set 1** — Theoretical (62) + Practical (23)
- **Set 2** — Theoretical (62) + Practical (23)

Each set keeps its own question IDs and can be selected independently in the app.

## Upload to GitHub

1. Go to GitHub and create a new repository.
   Example repository name: `ssw2-construction-study`

2. Open the new repository and choose:
   **Add file → Upload files**

3. Upload the CONTENTS of this folder to the root of the repository:
   - index.html
   - manifest.webmanifest
   - sw.js
   - .nojekyll
   - icons/

   Do not upload only the ZIP file.

4. Commit the uploaded files.

5. In the repository, open:
   **Settings → Pages**

6. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
   - Click **Save**

7. Wait a minute or two for GitHub Pages to publish the site.

Your address will normally look like:

`https://YOUR-GITHUB-NAME.github.io/ssw2-construction-study/`

## Install on iPad

1. Open the GitHub Pages address in **Safari**.
2. Confirm the questionnaire appears and works.
3. Tap the **Share** button.
4. Tap **Add to Home Screen**.
5. Tap **Add**.
6. Open **SSW2 Study** from the iPad Home Screen.

The installed version opens as a standalone PWA without the normal Safari address bar.

## Offline use

Open the installed app at least once while connected to the internet.
The service worker will cache the questionnaire and its local assets for offline use.

## Updating the questionnaire later

When replacing `index.html`, also change this line near the top of `sw.js`:

`const CACHE_NAME = 'ssw2-construction-pwa-v1';`

Change `v1` to `v2`, then `v3`, etc. This forces installed devices to refresh the cached version.

## Important

Do not try to install the PWA by opening `index.html` directly from the iPad Files app.
iPadOS file preview does not provide the normal HTTPS/service-worker environment required by a PWA.
