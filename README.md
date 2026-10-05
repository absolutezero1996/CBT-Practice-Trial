## Randomized answer choices

Answer choices are now randomized independently for every question.

- A fresh app/page opening creates a new choice order.
- **Reset progress** creates another new choice order.
- Choices do not move while you remain in the same practice session.
- Question order is still randomized independently.
- Correct-answer checking follows the shuffled position, so the original PDF answer letter/number is not exposed by position.
- Keyboard keys `1`–`4` select the currently displayed shuffled choices.

PWA cache version: `v13`.

## Furigana correction

Furigana was rebuilt and audited across every theoretical and practical set.

- Every kanji group in every question has an explicit hiragana reading.
- Every kanji group in every answer choice has an explicit hiragana reading.
- Missing readings and mixed kanji-without-reading cases, including the issues seen in Set 6, were corrected.
- Question text, answers, English translations, images, and answer keys were otherwise preserved.
- See `FURIGANA_AUDIT.txt` for the per-set validation summary.

PWA cache version: `v12`.

# SSW2 Construction Study

## Theoretical

The existing separate theoretical PDF sets are unchanged.

## Practical

- **Set 1** — Original sample — 23 questions
- **Set 2** — 実施3 — 55 questions

For Practical Set 2, the correct answer for each question is the choice highlighted
in yellow in `実施3(1).pdf`.

The uploaded `実施3(1).pdf` is byte-for-byte identical to the previously processed
`実施3.pdf`, so the previously extracted Japanese, furigana, English translations,
source images, source question numbers, and yellow-highlight answer choices were reused.

The repeated source Question 124 appears twice in the PDF; only one copy is stored,
leaving **55 source questions** in Practical Set 2.

## Current totals

- Theoretical: 443 questions
- Practical Set 1: 23
- Practical Set 2: 55
- **Total stored questions: 521**

PWA cache version: `v11`.
