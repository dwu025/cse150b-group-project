
# ChessLab (Group Project Starter Code)
Self-contained chess GUI + AI assignment.

- Rules: all standard moves **except** castling & en passant (omitted for clarity). Promotion->Queen.
- GUI: click piece then destination. Modes: Human vs Human, Human vs AI, AI vs AI.
- AI: You are required to implement any of the following: Random, Minimax, AlphaBeta (students implementations i.e. random/minimax/alphabeta, go in `chesslab/ai/ai.py`).
- Student work happens exclusively in `chesslab/ai/ai.py`. When submitting to Gradescope, upload only that file (`ai.py`).

Stages: random, eval, minimax, alphabeta.

## Group Members
- Di Wu (UCSD PID: A18550235)
## Abstract
- In this project, we will design and implement a chess artificial intelligence agent based on the provided ChessLab framework. This agent will be capable of competing against human players and other AI opponents. Starting from various stages, we will progressively enhance its performance and refine its algorithms. Starting with the random move, then move to heuristic evaluation. futhur more, will implant minimax search, explores future move sequences to select actions that maximize our agent’s chances of winning while assuming an optimal opponent. Add alpha–beta pruning for skipping over clearly bad branches and search deeper without taking extra time. By testing the agent by letting it play against itself, against human players, and by comparing how well the random, minimax, and alpha–beta versions perform to see where the ai can still be improved.
## Introduction
- build an AI agent that can play competitive chess

