# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/satsuki-sys/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/satsuki-sys/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python. Negamax alpha-beta search with PVS, quiescence search over captures, promotions and check evasions, a transposition table, null-move pruning, late move reductions, check extensions, and tapered piece-square evaluation with incremental scoring. It searches a fixed budget of 30,000 nodes per move, so every game replays move for move. It plays through the make.fun env protocol: it reads the env at MAKEFUN_ENV_URL and answers with UCI moves. The committed main.py is the makefun-compress/v1 packed form of the readable source.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=27qytqes&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
