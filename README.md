# 🕵️ Imposter

A pass-and-play party game for **3–99 players** on a single phone — like Spyfall / The Chameleon. **Four game modes:**

- **🃏 Words** — everyone gets the same secret word… except the **imposter(s)**, who only get a small hint. Take turns saying one related word, then discuss and vote.
- **💬 Questions** — everyone answers the same question… except the imposter(s), who secretly get a *different* question with a similar-sounding answer. Type your answers, reveal them all, and spot whose answer doesn't fit.
- **🕵️ Undercover** — everyone gets a word… except the imposter, who gets a *look-alike* (Dog vs Wolf). Describe your word one clue at a time — the imposter doesn't even know theirs is different.
- **🎚️ Wavelength** — everyone rates the same thing on a slider (Cheap ↔ Expensive)… except the imposter, who secretly rates a *different* thing. All the dials reveal at once — whose dot is the outlier?

**▶ Play it:** open [`index.html`](index.html) in any browser (works offline). On iPhone, use *Share → Add to Home Screen* to play it fullscreen like a native app.

## Features

- 🎮 **Four modes** — Words, Questions, Undercover, Wavelength — pick one on the home screen
- 🎨 Purple/black theme with a light-mode (purple/white) toggle
- 👥 3–99 players with custom names · 1–3 imposters (random option, "imposter never goes first")
- 🗂️ Words: **18 categories · 990 super-common words**, each with a safe 1–2 word imposter hint
- ❓ Questions: **6 categories · 400+ paired questions**, built so the imposter's answer lands in the same range
- ✏️ Add your own custom words *and* custom question pairs
- 🔒 Toggles: show category / show hint / imposters know each other
- 🎭 Animated reveal — the word cascades in letter by letter
- 🚫 A role locks the instant it's revealed, so nobody can peek twice
- 💾 Settings, mode, and theme persist between sessions

## How to play

1. **Start Round → set up** players, imposters, and categories.
2. Pass the phone around — each player taps their card, taps the box to reveal their role, then passes it on.
3. Non-imposters see the word; the imposter is told they're the imposter (plus an optional hint).
4. Going clockwise, everyone says **one word** related to the secret word — vague enough to be safe, clear enough to prove you know it.
5. Discuss, **vote**, and hit **Reveal Results** to see the imposter and the word.

Players win by catching the imposter; the imposter wins by surviving — or guessing the word.

## Tech

A single self-contained `index.html` — vanilla HTML/CSS/JS, no build step, no dependencies, fully offline. Inline SVG icons, CSS animations, and `localStorage` persistence.
