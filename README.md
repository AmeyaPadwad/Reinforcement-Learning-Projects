# 🎓 Reinforcement Learning Projects

## 📘 Course Overview

Course Instructor: **Prof. Mahdi Imani**  
Course Name: **Reinforcement Learning and Decision Making Under Uncertainty**  
Course Number: **EECE 5614**  
_Master’s Coursework – Northeastern University_

This repository contains all four major programming project assignments from EECE 5614, showcasing a progression from tabular methods to deep and policy-gradient based reinforcement learning approaches. Each assignment is a standalone module with clear documentation, training scripts, and results visualizations.

---

## 🗂 Project Summaries

### 🔹 Project 1: Multi-Armed Bandit and Action Selection Strategies

- **Objective**: Implement and analyze various action-selection strategies for a 2-armed bandit problem with unknown reward distributions.
- **Techniques**:

  - ε-greedy action selection
  - Stationary and non-stationary update rules with varying learning rates
  - Optimistic initial values
  - Gradient bandit method using softmax policies

- **Insights**: Compared the effectiveness of different learning rates and exploration parameters in terms of average accumulated reward over time. This project laid the foundation for reward estimation, value updates, and action-selection trade-offs.

---

### 🔹 Project 2: Dynamic Programming for Maze Navigation and Gene Network Control

- **Objective**: Apply **Policy Iteration** and **Value Iteration** methods to:

  1. Navigate a stochastic maze environment while avoiding penalties from oil, bumps, and walls.
  2. Control a 4-gene biological system (p53-MDM2 feedback network) to maximize gene activation.

- **Techniques**:

  - Vector-form Policy and Value Iteration
  - Custom reward shaping
  - State transition modeling using deterministic matrices and Bernoulli noise

- **Insights**: Demonstrated the effect of stochasticity and discounting on convergence, compared control policies under multiple system noise conditions, and measured long-run average gene activation as a performance metric.

---

### 🔹 Project 3: Temporal-Difference Methods and Actor-Critic Algorithms

- **Objective**: Solve two RL problems using **on-policy and off-policy TD methods**:

  1. Gridworld navigation with SARSA, Q-Learning, and Actor-Critic
  2. Binary-state control with stochastic Bernoulli transitions

- **Techniques**:

  - SARSA(0) and SARSA(λ)
  - Q-Learning
  - Tabular Actor-Critic (with TD error and eligibility traces)

- **Insights**: Compared sample efficiency, policy quality, and reward convergence across methods. Observed stability differences and sensitivity to learning rate and λ in stochastic environments.

---

### 🔹 Project 4: Deep Q-Networks for Stochastic Maze Solving

- **Objective**: Train a DQN agent to navigate a maze using (x, y) coordinates as state representation and reach a goal while avoiding high-penalty zones.
- **Techniques**:

  - DQN with replay memory and target networks
  - ε-decay strategy for exploration
  - Loss smoothing and performance visualization
  - Double DQN and Dueling DQN architectures

- **Insights**: Implemented and compared three deep RL variants. Showed improved training stability and policy quality with Double and Dueling DQNs. Produced final policies, value maps, and optimal paths for visual evaluation.

---

**Grade Summary**

| Project   | Score   |
| --------- | ------- |
| Project 1 | 50/100  |
| Project 2 | 100/100 |
| Project 3 | 100/100 |
| Project 4 | 95/100  |

---

## 🧠 Learning Outcomes

- Gained practical experience in implementing foundational and advanced RL algorithms from scratch, including:

  - Value-based methods (Dynamic Programming, TD, Q-learning)
  - Policy-based and Actor-Critic methods
  - Deep Reinforcement Learning with function approximation

- Learned to tune hyperparameters (α, γ, ϵ, λ, η) and assess convergence behavior
- Built stochastic environments and reward structures tailored to real-world constraints (e.g., biological networks, noisy transitions)
- Developed strong evaluation and debugging skills using visualizations, reward plots, and value-function heatmaps
- Gained intuition about the strengths, trade-offs, and appropriate use cases of tabular vs. function approximation methods

---
