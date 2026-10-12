# Midlands Tech 2026 Flashcards & Study Guides

A student-made study hub for **Midlands Technical College** students in Columbia, South Carolina. Choose a course from the home page and review course material in one place.

**▶️ Live app:** https://alexgoodestudio.github.io/midlands_technical_2026_flashcards/

## Courses

### BIO-101 · General Biology

Follows **OpenStax *Biology 2e*** and covers core introductory biology topics, including cells and metabolism, genetics, molecular biology, evolution, and ecology. Study with chapter-based flashcards, short-answer and essay practice, key-term definitions, memory aids, and a Final Prep section.

### CHM-110 · College Chemistry I

Follows **OpenStax *Chemistry 2e***. The current guide covers textbook review and course quiz material for Chapters 1–2, plus practice-sheet topics for Chapters 3–4, including measurement, atoms and ions, solutions, molarity, formulas, stoichiometry, limiting reactants, yield, and titration. Chemistry cards include explanations, worked practice, vocabulary support, and memory aids.

Both sections are organized for the **2026 classes**. The study hub is a work in progress, so the material may grow as the semester goes on.

## Features

- Biology and chemistry course sections from one home page
- Multiple-choice quiz and answer/self-check modes
- Explanations that show the reasoning behind answers
- Key-term definitions and textbook references
- Memory aids for concepts that are easy to mix up
- Progress saved in your browser
- Responsive layout for phones and desktops

## Run locally

Download or clone the repository, then open `index.html` in a browser. The app works without a build step or package installation; keep `chemistry.js` beside `index.html` so the chemistry section can load.

To serve it locally instead:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000/.

## About the material

This is a student-made study aid, not an official Midlands Technical College resource. Use it alongside your instructor's materials and check course-specific expectations with your instructor.

Biology content is based on **OpenStax *Biology 2e***. Chemistry material is adapted from **OpenStax *Chemistry 2e*** by Flowers, Theopold, and Langley (ISBN 9781947172616), licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). The chemistry study aid is shared under the same license. Some chemistry practice also follows course quiz and instructor practice-sheet material.

## Tech

The app uses HTML, CSS, and vanilla JavaScript. Biology content and interface are in `index.html`; chemistry study content and behavior are in `chemistry.js`. Study progress is stored in browser `localStorage`.

---

Built by Alex Goode while taking BIO-101 and CHM-110 at Midlands Technical College. © 2026.
