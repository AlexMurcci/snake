# 🐍 Snake

A modern take on the classic Snake — built as a **Telegram Mini App** with pure HTML5 Canvas, online leaderboards, and cross-device progress.

**[▶ Играть / Play Now](https://youngsanifone.github.io/snake/)** · открывается на весь экран в Telegram, в окне на десктопе.

---

## Features

- 🎮 Smooth canvas movement with delta-time physics
- 🎨 14 skins — 8 unlocked by leveling up, 6 bought for coins in the shop
- 🔊 Procedural music + sound effects (Web Audio API)
- 🔥 Combo system — eat food in a row for bonus points
- ⭐ Gold food and bonus items 🛡 ⚡ ❄ 💣
- 🏆 Online leaderboard with live presence
- 🎯 Quests, achievements and a coin shop
- 🌍 Multi-language UI (EN, RU, UK, PL, SK)
- 📱 Fullscreen on phones, fitted window on desktop

## Sign in

Two ways to save progress and sync across devices — no anonymous play:

- **Telegram** — one tap inside the Mini App
- **Email + password** — classic registration/login

Progress (best score, coins, level, skins) is stored server-side and follows you across devices.

## Controls

| Input | Action |
|-------|--------|
| ↑ ↓ ← → / WASD | Move |
| Swipe / D-pad | Move (mobile) |
| Space | Pause |

## Tech

Vanilla JavaScript — no frameworks, no build step, no dependencies.

- HTML5 Canvas 2D + Web Audio API
- Telegram Mini App SDK (`window.Telegram.WebApp`)
- Supabase backend — edge functions + Postgres for accounts, scores and leaderboard
- Hosted on GitHub Pages

## Development

The whole game is a single self-contained `index.html`. Open it in a browser to run locally — no server or install required. Pushes to `main` auto-deploy to GitHub Pages.
