🚀 Q-Learning for Route Optimization

This project demonstrates an implementation of Q-Learning, a reinforcement learning algorithm, to optimize decision-making and find the shortest path between locations in a defined environment.

📌 Project Overview

Objective: Use Q-Learning to determine the optimal route between two points, possibly with intermediary stops, in a network of connected locations.

Approach:

Define an environment with 12 states (A–L).

Use a reward matrix (R) to represent valid moves between locations.

Apply the Q-Learning algorithm with parameters γ (gamma) and α (alpha) to learn optimal state transitions.

Generate the shortest/optimal route between a start and end location.

⚙️ How It Works

Environment Setup:

States represent locations (A–L).

Actions correspond to moving between connected locations.

Rewards are defined based on allowed transitions.

Q-Learning Training:

The algorithm iteratively updates a Q-table by exploring actions.

Uses Temporal Difference (TD) learning for value updates.

Route Generation:

The trained model selects the highest-value actions to reach the destination.

Supports both direct routes and routes with intermediaries.

🛠️ Tech Stack

Python 3

NumPy (for matrix operations and randomness)
