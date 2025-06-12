# DR4DRL
Domain Randomization for Deep Reinforcement Learning Agents Trained for Financial Portfolio Management

## DR4DRL: Domain Randomization for Deep Reinforcement Learning Agents Trained for Financial Portfolio Management

This repository contains the code, data, and documentation associated with the thesis **"Domain Randomization for Deep Reinforcement Learning Agents Trained for Financial Portfolio Management"** by Max Vilarasau-Serra. The goal of this project is to improve the generalization capabilities of DRL-based trading agents using domain randomization (DR) techniques.

### 🧠 Abstract

Deep Reinforcement Learning (DRL) agents trained solely on historical financial data often suffer from overfitting and poor generalization in real-world markets. This project investigates the use of **Domain Randomization (DR)**—a technique popularized in robotics and sim-to-real transfer—to enhance the robustness of financial trading agents. By perturbing simulated market parameters during training (e.g., asset volatility, noise levels), we encourage agents to learn strategies that generalize across diverse market conditions.

We implement the **Deep Deterministic Policy Gradient (DDPG)** algorithm and evaluate agents trained with and without DR on Dow Jones data. Statistically significant improvements are observed in Sharpe ratios for agents trained with DR, demonstrating the potential of this technique as a regularizer in financial DRL.

