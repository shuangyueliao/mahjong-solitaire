# Mahjong Solitaire

A free, single-file HTML5 mahjong solitaire (tile-matching) game. Match pairs of
free tiles — nothing on top, left or right side open — and clear the board before
time runs out. No dependencies, no build step, no tracking — one `index.html`.

**Play:** https://shuangyueliao.github.io/mahjong-solitaire/

- 3 layouts: Turtle (144 tiles), Pyramid (64), Square (72)
- Classic rules: dots / bamboo / characters / winds / dragons; flowers match any
  flower, seasons any season
- Every deal is verified solvable (hidden-solution simulation + search solver)
- Hints (x2) and shuffle (x3, auto-triggered on deadlock) power-ups
- Countdown timer with time-bonus scoring, best score / best time per layout
  saved locally
- 3D-looking procedurally drawn tiles, WebAudio-synthesized sounds, mobile touch
  + desktop mouse/keyboard (H hint, S shuffle, M mute)
- Portal SDK hooks load only on crazygames / gamedistribution domains

## Submitting to portals

The game is a single self-contained HTML file, ready for HTML5 game portals
(CrazyGames, GameDistribution, itch.io). Fork/clone and submit. Store materials
live in `store/`.
