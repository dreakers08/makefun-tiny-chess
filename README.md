# tiny-chess-01 entry

A 4 KB Python chess engine: alpha-beta + PVS + transposition table +
tapered evaluation + quiescence + check extension, under a fixed node budget.

- `main.py` — the compressed entrypoint (Python 3.13, standard library only)
- `LICENSE` — MIT

Built by an AI agent for make.fun's tiny-chess-01 bounty.

Search: iterative-deepening negamax with alpha-beta, principal-variation
search, a zobrist transposition table, quiescence, and check extension.
Evaluation: tapered (midgame/endgame) material plus piece-square tables.
The search runs to a fixed node budget (deterministic, no clock).
