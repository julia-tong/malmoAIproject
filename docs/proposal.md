---
layout: default
title:  Proposal
---
## Summary
We will be recreating Tetris inside Minecraft. The inputs we would take in are: the current state of the game board, the incoming tetromino piece, and the next piece. It will output the placement and orientation of the incoming piece.

## AI/ML Algorithms
The algorithms we are thinking of using are genetic algorithms, simulated annealing, neural networks, and reinforcement learning.

## Evaluation Plan
Quantitative evaluation: For metrics, we will use a scoring system to compare the different states of the game. The baseline would be a regular user playing the game. We would expect our AI to improve the metric by a lot since it's much easier for the AI to keep the game going. The data we would evaluate on are the current state, the current/incoming piece, and the next piece.

Qualitative analysis: We would visualize the internals of the algorithm to verify that it works by analyzing the actual blocks that are in the tetris game. The AI should try to fill up all empty spaces and disallow any empty spaces past the bottom row.
