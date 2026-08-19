# IELTS Daily Audio Practice

A small open-source learning site for turning daily English diary feedback into repeatable IELTS practice.

The site focuses on three loops:

- Vocabulary memorization with pronunciation, meanings, and example sentences.
- Sentence-by-sentence speaking practice with browser speech audio.
- A positive-feedback dashboard that visualizes upgraded expressions, grammar progress, and topic mastery.

## Use

Open `index.html` or `ielts_daily_audio_practice.html` in a browser. Chrome and Safari usually provide the best Web Speech API voices.

## Add New Study Content

Edit the `studyData` array in `ielts_daily_audio_practice.html`.

Each date can include:

- `vocabulary`: grouped words with IPA, Chinese meaning, and examples.
- `article.sentences`: diary or speaking-answer sentences for one-by-one reading.
- `dashboard`: level-up expression pairs, grammar bugs, topic mastery, and positive feedback.

## Deploy

This project is static HTML, so it can be hosted with GitHub Pages:

1. Push the repository to GitHub.
2. Open repository Settings.
3. Enable Pages from the `main` branch root.

## License

MIT
