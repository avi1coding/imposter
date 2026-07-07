# 🕵️ Imposter

A pass-and-play party word game for **3–99 players** on a single phone — like Spyfall / The Chameleon.

Everyone gets the same secret word… except the **imposter(s)**, who only get a small hint. Take turns saying one related word, then discuss and vote on who's faking.

**▶ Play it:** open [`index.html`](index.html) in any browser (works offline). On iPhone, use *Share → Add to Home Screen* to play it fullscreen like a native app.

## Features

- 🎨 Purple/black theme with a light-mode (purple/white) toggle
- 👥 3–99 players with custom names
- 🕵️ 1–3 imposters, random-per-round option, and "imposter never goes first"
- 🗂️ **18 categories** · **990 super-common words**, each with a safe 1–2 word imposter hint
- ✏️ Add your own custom words
- 🔒 Toggles: show category / show hint / imposters know each other
- 🎭 Animated role reveal — the word cascades in letter by letter
- 🚫 A role locks the instant it's revealed, so nobody can peek twice
- 💾 Settings and theme persist between sessions

## How to play

1. **Start Round → set up** players, imposters, and categories.
2. Pass the phone around — each player taps their card, taps the box to reveal their role, then passes it on.
3. Non-imposters see the word; the imposter is told they're the imposter (plus an optional hint).
4. Going clockwise, everyone says **one word** related to the secret word — vague enough to be safe, clear enough to prove you know it.
5. Discuss, **vote**, and hit **Reveal Results** to see the imposter and the word.

Players win by catching the imposter; the imposter wins by surviving — or guessing the word.

## Tech

A single self-contained `index.html` — vanilla HTML/CSS/JS, no build step, no dependencies, fully offline. Inline SVG icons, CSS animations, and `localStorage` persistence.
