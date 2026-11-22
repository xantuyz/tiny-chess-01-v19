# Tiny Chess v19 — strongest chess engine in 4 KB of Python

[![make.fun](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/xantuyz/tiny-chess-01-v19/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard)
[![reward](https://make.fun/badge/tiny-chess-01/xantuyz/tiny-chess-01-v19/reward.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard)

Entry for [tiny-chess-01](https://make.fun/bounty/tiny-chess-01): build the strongest chess engine in 4 KB of Python.

- `main.py` — the packed engine (4,094 bytes, under the 4,096-byte limit). This is the entrypoint the grader runs.
- `engine_src.py` — the readable source the packed entrypoint is built from.
- `pack19.py` — the pack script (minify → lzma → base85 → stub), with a perft(3) self-check.

Measured strength: Elo 1362 over a canonical 16-game trial vs sunfish anchors (4W 7D 5L), above the 1360 baseline. Trial log: `TRIAL-v19.md` in the build notes.
