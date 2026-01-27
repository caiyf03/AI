# Hearts Game AI System

This repository contains the official implementation for **Hearts Game AI System**

The main text of the paper can be found at: [final report.pdf](final%20report.pdf)

This project develops an AI agent for the Hearts card game, a multi-player, imperfect-information environment requiring strategic reasoning and long-term planning. The goal is to compare classical search-based and learning-based decision-making methods under realistic game constraints.

**Key Features**

-Supports multiple AI paradigms within a unified game engine

-Adaptive MCTS for improved runtime–performance trade-offs

-State abstraction enabling Q-learning in large, discrete action spaces

-Simulation and visualization tools for strategy comparison and analysis

**Methods**

We implemented and evaluated greedy, Monte Carlo Tree Search (MCTS), and Q-learning agents. MCTS handles uncertainty through randomized rollouts and includes an adaptive variant that reduces computation when the agent is ahead. To enable learning in a large state space, the Q-learning agent uses state abstraction and reward shaping, learning strategic behavior through repeated self-play.

**Results**

Experiments over simulated games show that MCTS achieves the strongest performance at the cost of higher computation, while the Q-learning agent outperforms greedy and random baselines with improved adaptability. The results highlight trade-offs between decision quality, efficiency, and learning capability in imperfect-information games.


![](pic/1.png)
![](pic/2.png)
![](pic/3.png)
