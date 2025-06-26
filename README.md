# Reinforcement Learning Based COVID Policy Search

This project explores the application of various **reinforcement learning (RL)** algorithms to evaluate and design effective policy interventions for managing the spread of **COVID-19**. By simulating different approaches, we aim to understand how RL techniques can inform public health strategies.

---

## Implemented Algorithms

The following reinforcement learning methods were implemented and tested:

### Policy Search with Linear Function Approximation (`ps_lfa`)
A policy optimization technique that uses a linear approximation of the policy function.

### Policy Search with Tabular Method (`ps_tm`)
A basic policy search method where states and actions are represented in a lookup table.

### Q-Learning with Neural Network (`qlearnnn`)
A deep Q-learning approach that uses a neural network to approximate the Q-function.

### Q-Learning with Tabular Method (`q_learning_tm`)
A traditional tabular Q-learning algorithm that maintains Q-values for state-action pairs.

---

## Environment

- **virl** — The specific reinforcement learning environment developed for this project to simulate COVID-19 dynamics and policy effects.

