## Current question banks

### Theoretical
- **Set 1:** 62 existing sample questions
- **Set 2:** 421 questions from `学科練習 01.pdf` through `学科練習 11.pdf`
  - Practice 01: 21 questions
  - Practice 02–11: 40 questions each
  - 23 source figures/photos/graphs are embedded

### Practical
- **Set 1:** 23 existing practical sample questions
- **Set 2:** 55 implementation-practice questions

Theoretical Set 2 preserves the 11 uploaded practice papers as separate selectable
`Practice 01` through `Practice 11` groups. The source PDFs do not provide English
translations for these theory questions, so Japanese/furigana remain the source-grounded
study text and English mode displays the source-not-available notice.

## Practical question banks

The Practical section now has two separate banks:

- **Set 1:** 23 existing practical sample questions
- **Set 2:** 55 unique questions from `実施3.pdf` / `[Blank] 実施1.pdf`

The two uploaded PDFs contain the same new practical-question collection in answer/translated and blank forms. One repeated source Question 124 was removed from Set 2, leaving 55 unique questions.

Set 2 retains the source question numbers, answer highlights from the annotated PDF, furigana, English wording where supplied, and 14 source images.

# SSW2 Construction Study — Merged / Deduplicated

Set 1 and Set 2 were compared and found to contain the same question content.

The duplicate questionnaire-set selector has therefore been removed.

Current unique question bank:

- **Theoretical: 62**
  - Sample Questions: 34
  - Additional Sample: 28
- **Practical: 23**
  - Sample Questions: 7
  - Additional Sample: 16

Total: **85 unique questions**

## Updating GitHub Pages

Upload/replace these files in the root of your existing GitHub Pages repository:

- `index.html`
- `sw.js`
- `manifest.webmanifest`
- `.nojekyll`
- `icons/`

You do not need to change Settings → Pages again.

The service-worker cache version is now `v4`, so installed iPad PWAs should refresh to this merged build after reopening/reloading the site.
