# Grid World Q-Learning Agent

A simple reinforcement learning project that implements **Q-Learning** to solve a 4×4 Grid World environment using Python and NumPy.

## Overview
An agent starts at the top-left corner of the grid and learns the optimal path to reach the goal at the bottom-right corner using rewards and penalties.

## Key Concepts
- Reinforcement Learning
- Q-Learning
- ε-greedy exploration
- Discrete state-action space

## Environment
- Grid size: 4 × 4
- Actions: Up, Down, Left, Right
- Rewards:
  - +10 for reaching the goal
  - -1 for each step

## Requirements
- Python 3.x
- NumPy

Install NumPy:
```bash
pip install numpy
