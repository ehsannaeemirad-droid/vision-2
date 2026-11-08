# Vision 2 · Interactive English Book

Interactive digital version of **Vision 2** (English textbook for Iranian Grade 11 students) with:

- **Book-style page viewer** – layout close to the original textbook
- **Study (Easy) mode** on every section – word cards + sentence building with Persian meanings
- **Flashcards** – save words while studying and review later
- Text-to-speech for English words and sentences

## Live demo

After enabling GitHub Pages on the `main` branch (Settings → Pages → Deploy from branch → `/root`):

**https://ehsannaeemirad-droid.github.io/vision-2/**

## Sections covered (Lesson 1)

| Section | Pages | Study mode |
|---------|-------|------------|
| Get Ready | 17–18 | ✅ |
| Conversation – Mr. Saberian | 19–20 | ✅ |
| New Words & Expressions | 21–23 | ✅ |
| Reading – Languages of the World | 24–26 | ✅ |
| Grammar – Countable / Uncountable | 28–31 | ✅ |
| Listening & Speaking – Shopping | 34–35 | ✅ |
| Writing – Simple Sentences | 37–45 | ✅ |

## How to use

1. Open the home screen and choose a section.
2. Read the book-style page (placeholders used for original images).
3. Tap **📚 مطالعه (Easy)** to enter interactive study mode.
4. Learn words, build sentences, save flashcards.
5. Review saved cards from the 🗂️ button in the header.

## Tech

- Single `index.html` (no build step)
- LocalStorage for flashcards
- Web Speech API for pronunciation
- Vazirmatn + Inter fonts

## Related

Original study app with more advanced modes:  
[english-lesson-1](https://github.com/ehsannaeemirad-droid/english-lesson-1)
