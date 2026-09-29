# 🍅 Pomodoro Timer — Day 4 (simple build) of my daily coding journey

A beautiful, no-dependency **Pomodoro focus timer** in a single HTML file. Work in focused bursts, take real breaks, and watch your completed sessions stack up.

## Why this exists

The Pomodoro Technique is simple: 25 minutes of deep focus, 5 minutes of rest, and a longer break every 4 sessions. This timer makes it effortless — no sign-up, no install, works offline once saved.

## ✨ Features

- 🎯 **Focus / Short Break / Long Break modes** — auto-advances when a session ends
- ⏱️ **Animated progress ring** that drains as time passes, color-coded per mode
- 🔔 **Chime sound** (Web Audio — zero audio files needed) when a session finishes
- ⚙️ **Customizable durations** — change focus/break lengths right on the page
- 🍅 **Session tracker** — dots fill up as you complete focus sessions
- ⏸️ **Start / Pause / Reset** controls, plus a live countdown in the browser tab title
- 📱 Responsive, mobile-friendly dark UI

## 🚀 Run it in 30 seconds

1. Download `index.html` (or clone this repo)
2. Double-click it — it opens in your browser
3. Hit **Start** and get to work 🍅

No build step. No dependencies. No server.

## 📸 What you see

```
┌─────────────────────────┐
│        🍅 POMODORO      │
│   [Focus][Short][Long]  │
│      ╭─────────╮        │
│      │  25:00  │  ← big countdown ring
│      ╰─────────╯        │
│   Session 1 of 4 · focus│
│   [Start]    [Reset]    │
│  Focus: 25  Short: 5    │
│  Completed sessions ●···│
└─────────────────────────┘
```

## 🧠 What I practiced

- DOM manipulation and event listeners
- `setInterval` / `clearInterval` timer logic
- SVG circular progress ring (stroke-dasharray math)
- Web Audio API for the chime (no audio assets)
- CSS custom properties for theming

## 🔁 The streak

This is **Day 4** of my daily coding journey — one simple and one featured build every day. See the full streak on my profile: [github.com/OBG-ent](https://github.com/OBG-ent)
