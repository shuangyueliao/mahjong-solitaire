# Mahjong Solitaire — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io, 197 chars)

Match pairs of free mahjong tiles and clear the board before time runs out.
3 layouts (Turtle 144, Pyramid 64, Square 72), hints, shuffles, and a fresh
solvable deal every game.

## Details

- Genre: Puzzle / Board / Casual
- Controls: Mouse / Touch (tap two free tiles with the same face). Keyboard:
  H hint, S shuffle, M mute, Esc menu.
- Rules: a tile is free when nothing rests on it and its left or right side is
  open. Flowers match any flower; seasons match any season. Clear everything
  for a remaining-time bonus (x2 seconds).
- Features: 3 layouts (Turtle 144 / Pyramid 64 / Square 72), countdown timer,
  hint (x2) and shuffle (x3, auto-triggered on deadlock) power-ups, best score
  & best time per layout saved locally, procedurally drawn 3D tiles and
  WebAudio sounds, single-file HTML5 (no external assets), works offline once
  loaded.
- Tech: Vanilla JavaScript, Canvas, WebAudio. No frameworks, no tracking.
  Every generated board is verified solvable (hidden-solution simulation plus
  an independent search solver); deadlocks reshuffle into a still-solvable
  board.

## Tags
mahjong, solitaire, puzzle, board, tiles, matching, casual, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales to any viewport, mobile portrait verified)
- [x] No external links inside gameplay, no analytics
- [ ] Cover 16:9 (1280x720) — capture from live game
- [ ] Screenshots (1280x800) — capture from live game

## GameDistribution
- Upload mahjong-solitaire-gd.zip (contains index.html only, entry file at zip
  root).

## itch.io
- Upload zip (rename to mahjong-solitaire.zip), mark "This file is playable in
  browser", entry file: index.html, kind: html. Recommended viewport: fill
  window (game is fully responsive).
- Pricing: $0 (donations optional)
