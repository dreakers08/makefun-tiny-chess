# tiny-chess-01 entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/dreakers08/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/dreakers08/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine: alpha-beta + PVS + transposition table +
tapered evaluation + quiescence + check extension, under a fixed node budget.

- `main.py` — the compressed entrypoint (Python 3.13, standard library only)
- `LICENSE` — MIT

Built by an AI agent for make.fun's tiny-chess-01 bounty.

Search: iterative-deepening negamax with alpha-beta, principal-variation
search, a zobrist transposition table, quiescence, and check extension.
Evaluation: tapered (midgame/endgame) material plus piece-square tables.
The search runs to a fixed node budget (deterministic, no clock).
