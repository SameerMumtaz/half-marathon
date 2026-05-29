[README.md](https://github.com/user-attachments/files/28376207/README.md)

# 13.1 — Half Marathon Training Plan

A personal, interactive training plan for the **Dallas Half Marathon, December 13, 2026**. Built as a single self-contained HTML file with offline-capable progress tracking.

🏁 **Race day:** Sun, Dec 13, 2026 · Dallas, TX · 13.1 mi
🚀 **Training start:** Wed, May 27, 2026 (200 days of work)
🏋️ **Format:** Hybrid — 4× strength training + 3-4× running per week

---

## What this is

A 29-week, 5-phase training plan designed around real-life constraints:

- **Hybrid athlete schedule** — preserves a 4-day Push/Pull/Legs + accessory lifting split alongside run training
- **Dallas summer climate** — early-morning runs, indoor lifts, heat-acclimation buffer through August
- **Beginner-friendly progression** — starts with run/walk intervals, builds to continuous running, ends at full 13.1 mi capability
- **Smart taper** — both running volume and lifting intensity reduce in the final 3 weeks for fresh legs on race day

## Features

- ✅ **Checkable workouts** with progress saved locally (per-device)
- 🕐 **Total session time** displayed for every workout
- 📏 **Estimated mileage** for every run
- 📊 **Pace guide** with mph + min/mi targets for all run types
- 🗓️ **Auto-detects current week** based on today's date
- ⏳ **Live countdown** to race day
- 📱 **iOS web-app meta tags** — adds to Home Screen as a near-native app
- 🌙 **Dark theme** optimized for early-morning runs and gym lighting

## Phase overview

| Phase | Weeks | Focus |
|-------|-------|-------|
| **01 · Foundation** | 1–6 | Run/walk intervals, building base from zero |
| **02 · Base** | 7–12 | Continuous easy running, Dallas heat survival |
| **03 · Build** | 13–16 | Long runs up to 7 mi, adding 4th weekly run |
| **04 · Sharpen** | 17–27 | Tempo runs, intervals, long runs build to 13 mi |
| **05 · Race** | 28–29 | Taper for both lifting and running, race execution |

## Weekly template

| Day | Workout |
|-----|---------|
| **Mon** | Legs (heavy) |
| **Tue** | Pull + easy run |
| **Wed** | Push + easy run *(from Phase 3)* |
| **Thu** | Quality run *(tempo/intervals from Phase 4)* |
| **Fri** | Light accessory (upper, no legs) |
| **Sat** | Long run |
| **Sun** | Full rest |

## How to use

1. Open `index.html` in Safari on iPhone (or any modern browser)
2. **Add to Home Screen** for native app feel:
   - Safari → Share → Add to Home Screen → name it "13.1"
3. Each day, open the app and check off completed workouts
4. Progress saves to your device's localStorage automatically

## Tech notes

- **Stack:** Pure vanilla HTML + CSS + JavaScript. No frameworks, no build step, no dependencies.
- **Storage:** `localStorage` (primary) with optional cloud sync fallback. Per-device persistence.
- **Fonts:** Bebas Neue, IBM Plex Sans, IBM Plex Mono (via Google Fonts CDN).
- **No backend.** Single HTML file, fully self-contained. Works offline after first load.

## Cross-device sync?

This is a **single-device** plan by design. If you check workouts on your phone, the data lives only on your phone. For cross-device sync, you'd need a backend (Firebase, Supabase, etc.) — not included here.

## Updating the plan

To update the HTML:
1. Edit `index.html` (or replace with a new version)
2. Commit & push
3. GitHub Pages rebuilds in ~60 seconds
4. Refresh on your phone — checked workouts are preserved (they live in localStorage, not in the file)

## Disclaimer

This is a personal training plan, not medical or professional coaching advice. Consult a physician before starting any training program, especially if you have existing health conditions. The plan reflects best-effort programming based on general training principles for a beginner-to-intermediate runner with a strength training background.

---

**Built for one runner. Built to ship. 200 days. Let's go.**
