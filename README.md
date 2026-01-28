# Cs6380AI

This repository contains two course projects:

1) Othello AI (folder: `1.othello/Desdemona`)
- A C++ implementation of an Othello engine and an AI bot.
- The AI uses multiple game heuristics and prunes the minimax search with alpha–beta pruning to optimise move selection.
- Directory highlights:
  - `src/`, `include/`, `lib/`, `obj/` — engine source, headers and build artifacts.
  - `bots/` — example bots (RandomBot, SlowBot, TuringBot, MyBot) with Makefiles; `bin/Desdemona` is a built executable.
- Build/run: change into `1.othello/Desdemona` and use the provided `Makefile` to build the engine and bots (e.g. `make`). Consult `bots/` Makefiles for building individual bots.

2) Travelling Salesman Problem (folder: `2.Travelling_SalesMan_Problem`)
- A TSP implementation with source `main.cpp` and a problem description in `TSP_problem.pdf`.
- A `Makefile` and `run` script are provided for compilation and execution.
- Build/run: `cd 2.Travelling_SalesMan_Problem && make` then run `./run` (or execute the produced binary directly).

Why these are useful
- The Othello project demonstrates classical AI techniques: evaluation heuristics, game-state representation, and search-space pruning (alpha–beta), useful for learning adversarial search and performance tuning in C++.
- The TSP project provides a practical implementation and problem statement useful for experimenting with combinatorial optimisation and heuristic/exact algorithms.

