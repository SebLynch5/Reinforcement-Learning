# Reinforcement Learning in Gridworld

This project explores reinforcement learning (RL) techniques by training an agent to navigate a maze-like environment known as Gridworld. The goal is for the agent to reach a reward while avoiding obstacles, using two RL methods: **Value Iteration** and **Q-Learning**.

## Overview

- **Value Iteration**: A model-based approach that updates value functions based on known transitions.
- **Q-Learning**: A model-free approach where an agent learns optimal actions from reward feedback.

The agent learns policies to maximise cumulative rewards while avoiding spikes and reaching cheese (goal states).

## Key Results

- **Value Iteration**: Accurately computes an optimal policy efficiently.
- **Q-Learning**: Slower and less complete on small maps, but more scalable to dynamic or unknown environments.
- Decaying exploration in Q-learning improves performance by balancing exploration and exploitation.

Full findings and visuals are presented in the [Report](./Reinforcement%20Learning%20Report.pdf).

## Files

- `Reinforcement_Learning.ipynb` – Google Colab notebook implementing both methods.
- `Reinforcement Learning Report.pdf` – Coursework report with visualisations, analysis, and conclusions.

## How to Run

You can open the notebook in [Google Colab](https://colab.research.google.com/) directly.

No additional data or packages are needed outside of standard Python libraries (`numpy`, `matplotlib`).
