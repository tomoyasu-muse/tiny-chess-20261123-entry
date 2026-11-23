# tiny-chess-20261123-entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/tomoyasu-muse/tiny-chess-20261123-entry/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/tomoyasu-muse/tiny-chess-20261123-entry/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: 0x88 board, negamax with alpha-beta, quiescence search, transposition table, killer and history move ordering, piece-square tables with an endgame king taper, and iterative deepening to a fixed node budget (fully deterministic, no clock, no randomness). It plays the house gauntlet through the env at `MAKEFUN_ENV_URL`.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

`main.py` is the packed entrypoint (see `engine.py`, the readable source it was packed from with the kit's `makefun compress`).

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
