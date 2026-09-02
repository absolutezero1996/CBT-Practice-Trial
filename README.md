## Set 2 deduplication

Repeated questions inside Set 2 have been removed while retaining one clean copy.

### Current counts
- Theoretical Set 1: 62
- **Theoretical Set 2: 377** (44 duplicate copies removed)
- Practical Set 1: 23
- **Practical Set 2: 54** (1 duplicate copy removed)

Total question records in the app: **516**.

Questions that merely cover a similar topic but use a different image, ask a different fact,
or provide meaningfully different choices were retained.

See `DUPLICATES_REMOVED.txt` for the duplicate pairs/groups that were removed.

The PWA cache version is `v8`.

# SSW2 Construction Study - English Fixed

English is populated for every question and every answer option.

## Question banks

### Theoretical
- Set 1: 62 questions
- Set 2: 421 questions
  - Practice 01: 21
  - Practice 02-11: 40 each

### Practical
- Set 1: 23 questions
- Set 2: 55 questions

Practical Set 2 retains the English wording supplied with the translated practical PDF.
Theoretical Set 2 English was translated from the Japanese wording in `学科練習 01.pdf`
through `学科練習 11.pdf`.

## GitHub Pages update

Replace the files in the root of your existing GitHub Pages repository with the
contents of this ZIP. In particular, replace `index.html`, `sw.js`, and
`manifest.webmanifest`, and upload the `icons` folder and `.nojekyll`.

The cache name is `ssw2-construction-pwa-v7`, so existing PWA installations should
receive the updated version after reopening/reloading the site.
