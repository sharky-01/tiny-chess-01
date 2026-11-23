# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/sharky-01/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/sharky-01/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 3,280-byte Python chess engine: negamax alpha-beta with a transposition table, quiescence search, null-move pruning and an 80,000-node move budget. Practice Elo 1,274 on the make.fun gauntlet. In practice trial 0 the revised engine scored 2 wins, 2 draws, 2 losses (Elo 1,279).

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 main.py
```

## Validation

The engine passed perft checks (startpos and kiwipete positions, exact node counts) and practice trial 0 (2 wins, 2 draws, 2 losses). `main.py` is the make.fun kit compressor's packing of `engine.py`, at 3,280 bytes.

---

<sub>Entered on [make.fun](https://make.fun/?ref=y582cdjt&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
