# Recall - flashcards that remember for you

A spaced-repetition flashcard trainer in a single HTML file, with a **notes -> flashcards generator** that reads your study material and drafts the cards for you - including exam-style long-answer questions and diagrams.

## Build cards from your notes
- **Paste text**, or **upload a PDF, an image of your notes, or a .txt / .md file**
- Reads it **on your device** - nothing is uploaded, no account, no key
- **Exam questions**: detects numbered / "Q1." questions with mark allocations (10 marks, 5 marks...) and keeps the **exact full answer**, paragraph by paragraph
- **Definitions**, Q&A pairs, headings, and fill-in-the-blank cards from key sentences
- **Diagrams**: crop a diagram straight out of a PDF page (or an uploaded image) and attach it to any card - it then shows on the card while you study
- Long answers are kept in full and render in a scrollable card, not cut off
- Choose how many cards, pick which styles you want, then **review and edit every card** before adding it to a deck
- PDFs are read with pdf.js when online, with a built-in offline reader as a fallback; images are read with OCR (needs a connection the first time)

## Study features
- Multiple decks: create, rename, delete
- Leitner-style scheduler with five boxes (1, 3, 7, 16, 35 day intervals)
- Three grades per card - **Again / Good / Easy**
- Session summary with cards reviewed, recall % and time
- Keyboard shortcuts: `space` to flip, `1` `2` `3` to grade
- Import decks from JSON (images included)

## Run it
Download `index.html` and open it in any modern browser, or enable GitHub Pages. No build step, no dependencies, no server.

## Your data
Everything is saved in your browser's local storage and never leaves your device.

---
Part of a set of self-contained browser apps. Design: warm *paper & ink* editorial.
