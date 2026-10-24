# Rotation Station (2.18.0 · 2026-10-22)

Fair minutes and subs for youth basketball coaches. A free phone web app for youth basketball coaches: it plans who plays when so every player gets fair minutes, tells you when to sub, and tracks score, fouls and timeouts during the game.

**Open it:** https://kramkroc.github.io/rotation-station/
**iPhone:** open in Safari → Share → *Add to Home Screen*. **Android:** open in Chrome → ⋮ → *Install app*.
Open it once with signal; after that it works offline.

## Privacy
No account, no tracking, no server. Everything (names, minutes, scores) is stored only in the browser on your phone. Nothing leaves the phone unless you copy it out yourself.

## First use
Setup tab → type your team name, then edit the squad (names, numbers, tiers). Defaults follow Basketball NI / FIBA youth rules (4 × 8-minute quarters); change them in Setup.

## Publishing (for the maintainer)
1. Create a public GitHub repo, upload every file in this folder (including `.nojekyll`) to the root.
2. Settings → Pages → Deploy from a branch → `main` / `/ (root)`. The link appears after a minute or two.
3. To update: run `node build-public.js` again and upload the new files over the old ones.

## Support
Free to use. If it helps your team, you can [Buy me a coffee](https://ko-fi.com/rotationstation).

## Licence
MIT — see LICENSE.
