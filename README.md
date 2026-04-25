# Polyglot Quest

A self-contained, browser-based language learning app. Five languages (Spanish, French, Japanese, German, Italian) with vocabulary lessons, pronunciation guides, cultural quizzes, idiomatic expressions, fill-in-the-blank exercises, an AI tutor (bring your own Anthropic API key), achievements, and an activity heatmap.

## Live demo

Once GitHub Pages is enabled: https://pebretones.github.io/polyglot-quest/

## Features

- 📚 **Vocabulary lessons** with flashcards and native pronunciation (browser TTS)
- ✏️ **Practice** — fill-in-the-blank cloze exercises
- 👄 **Pronunciation Lab** with physical how-to for tricky sounds + speech recognition (Chrome/Edge)
- 💡 **Native expressions & idioms** with literal translations and usage examples
- 🎭 **Culture quiz** — trivia across history, food, art, cinema
- 💬 **AI tutor** powered by Claude (your own API key, never leaves the browser)
- 🎬 **Films, books, music** curated by language and difficulty
- 🏆 **Achievements** that unlock as you progress
- 📅 **Activity heatmap** GitHub-style
- 🔐 **Local accounts** — passwords hashed in-browser, multiple users on one device

## Tech

Single static HTML file. No build step, no backend. Data lives in `localStorage`. Works offline once loaded (except AI tutor and Google Fonts).

## Local development

```bash
node serve.js
# then open http://localhost:8000/
```

## License

MIT
