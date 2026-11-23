# tiny-chess-01 entry

A 4 KB chess engine: 0x88 board, negamax with alpha-beta, iterative deepening
to a fixed node budget, quiescence, transposition table, killer moves and
simplified piece-square evaluation. `main.py` is an lzma-packed form of the
readable `engine.py` source, made with `makefun compress`.

Run: `python3 -P -s main.py` with `MAKEFUN_ENV_URL` set.
