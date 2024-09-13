# **BURST**: Bayesian Uncertainty-driven Reinforcement Sampling Technique

### Overview

Our method integrates uncertainty estimation into the action selection process of a Deep Q-Network (DQN) agent. The agent uses a Bayesian neural network to model the Q-function, providing both expected Q-values and uncertainty estimates for each action. The uncertainty estimates guide the exploration strategy.

### Key Components

1. **Bayesian Deep Q-Network (BDQN)**: Extends the standard DQN with Bayesian neural networks to estimate uncertainty in Q-value predictions.
2. **Uncertainty-Driven Exploration**: Uses the uncertainty estimates to prioritize exploration of actions with high uncertainty.
3. **Thompson Sampling**: Implements Thompson Sampling for action selection, sampling from the posterior distribution over Q-values.
