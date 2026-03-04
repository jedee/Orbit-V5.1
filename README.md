# Orbit v2 — Daily Rings for Nigeria

## Deploy to GitHub Pages
```bash
git clone https://github.com/jedee/orbit
cd orbit
cp /path/to/orbit-v5/* .
git add . && git commit -m "Orbit v2" && git push
```
Settings → Pages → main branch / root → Save

Live at: `https://jedee.github.io/orbit`

## Features
- Daily rings (reset midnight) with calendar history
- Streaks + 6-level progression system
- 9 achievements
- Friends via Orbit ID (leaderboard)
- Full finance tracker
- All data stays on device (localStorage)

## Live Friends
For real-time friend sync, connect a free Firebase Firestore project.
Friends only ever see rings + streak. Spending is always private.
