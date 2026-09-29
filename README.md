# 🟩 Wordly — a Wordle clone — Day 4 (featured build) of my daily coding journey

Guess the 5-letter word in 6 tries. Green means right letter, right spot. Yellow means right letter, wrong spot. Gray means it's not in the word at all. You know the drill — but this one is **mine**, built from scratch.

## ✨ Features

- 🎮 **Full Wordle gameplay** — 6 guesses, correct duplicate-letter logic, word-list validation
- ⌨️ **On-screen + physical keyboards** — type or tap, with key colors updating as you learn
- 🎞️ **Flip + pop + shake animations** for tile reveals and invalid guesses
- 📊 **Stats that persist** — games played, win %, current streak, best streak (localStorage)
- 📤 **Share your result** — one click copies the emoji grid (`🟩🟨⬛`) like the real thing
- 🌙 **Dark / light mode** toggle (saved between visits)
- 📖 600+ word dictionary for answers and guesses

## 🚀 Run it in 30 seconds

1. Download all files (`index.html`, `styles.css`, `script.js`, `words.js`) into one folder
2. Double-click `index.html`
3. Start guessing — use your keyboard or the on-screen keys

No build step. No dependencies. No server.

## 📸 What you see

```
┌───────────────────────────┐
│        WORDLY             │
│  ⬛ ⬛ ⬛ ⬛ ⬛            │  ← 6 rows of tiles
│  ⬛ ⬛ ⬛ ⬛ ⬛            │
│  🟨 ⬛ 🟩 ⬛ 🟨            │  ← revealing after Enter
│  ...                      │
│  [Q][W][E][R][T][Y]...    │  ← color-coded keyboard
│  📤 Share result  🔄 Play │
│  Played 4 · Win 75% · 🔥 3│
└───────────────────────────┘
```

## 🧠 What I practiced

- Game-state management and input handling (two keyboard sources, one handler)
- Two-pass letter evaluation algorithm that handles duplicate letters correctly
- CSS animations: keyframe flip, pop, and shake
- `localStorage` for stats + theme persistence
- Clipboard API for the share button

## 🔁 The streak

This is **Day 4** of my daily coding journey — one simple and one featured build every day. Full streak on my profile: [github.com/OBG-ent](https://github.com/OBG-ent)
