# tiny-chess-4k

A chess engine in under 4 KB of Python for make.fun's tiny-chess-01: 0x88 board, negamax with alpha-beta, quiescence search, a transposition table, killer moves and piece-square evaluation, searching to a fixed node budget. Deterministic: no clock, no randomness, no model calls.

Local practice mean Elo 1441 (trials 0/1/2: 1396/1530/1396) vs the sunfish baseline mean 1325.
