# EPS-TOPIK 반대말 + 비슷한 말 Quiz — 400 Questions

Live site: https://sudip-pandey.github.io/eps-topik-similar-opposite/

Opposite words (반대말, Q1–200) and similar words (비슷한 말, Q201–400) from the 99-page EPS-TOPIK question book (Notes_261124_102457.pdf).

## Entry flow

- `index.html` is a chooser: two cards, Opposite (반대말) and Similar
  (비슷한 말). Whichever the viewer picks, that section starts from
  question 1 — `antonym.html` (200 antonyms, numbered 1–200) or
  `synonym.html` (200 synonyms, numbered 1–200).
- `full-quiz.html` — all 400 questions in one file.
- `set-01`–`set-08` — 8 sets of 50 questions each.

- 20 questions per page, progress auto-saves per file (localStorage,
  separate key per file so section/set/full progress never collide).
- The book has NO printed answer key — answers and Nepali explanations
  are AI-researched.
- Book defect corrected: antonym 마르다 is printed as 66 but is book 65
  (the book skipped 65); 입구 printed 66 is book 66.
- Theme: single-color indigo (solid header #312e81, accent #4f46e5).
