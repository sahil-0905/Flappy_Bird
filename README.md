# Flappy Bird AI — Deep Reinforcement Learning

## About the Project

This project focuses on building an AI agent that learns to play the Flappy Bird game using **Reinforcement Learning (RL)** and **Deep Learning**.

The agent interacts with the game environment, observes the current state, takes actions, and receives rewards or penalties. Through repeated interactions, it aims to learn a policy that improves its gameplay performance.

The project is being developed using the **Deep Q-Network (DQN)** approach, with the goal of implementing **Double DQN** to improve value estimation during learning.

## Tech Stack

- **Python**
- **PyTorch** — Deep Learning
- **Gymnasium** — Reinforcement Learning environment
- **Flappy Bird Gymnasium** — Game environment
- **NumPy** — Numerical computations
- **Experience Replay** — Storing past transitions for training

## Key Concepts

- Reinforcement Learning
- Deep Q-Network (DQN)
- Double DQN
- Reward-based learning
- State and action spaces
- Experience Replay
- Neural Networks

## Project Workflow

1. Initialize the Flappy Bird environment.
2. Observe the current state of the game.
3. Select an action for the agent.
4. Execute the action and collect the reward.
5. Store state transitions in replay memory.
6. Train the neural network to learn better action values.
7. Evaluate the agent's performance over multiple episodes.

## Current Status

**In Development** 🚧

The environment setup and initial interaction loop are being developed. The next steps include implementing the complete DQN training pipeline, adding Double DQN updates, and evaluating the trained agent.

## Learning Objectives

- Understand how reinforcement learning agents interact with environments.
- Implement deep reinforcement learning using PyTorch.
- Learn how experience replay supports stable training.
- Explore the difference between standard DQN and Double DQN.
- Evaluate agent performance using episode rewards.

## Future Improvements

- Complete the DQN training loop.
- Implement the Double DQN algorithm.
- Track episode rewards and training progress.
- Save and load trained model weights.
- Compare DQN and Double DQN performance.

## Installation

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
cd YOUR_REPOSITORY_FOLDER
```

Install the required dependencies:

```bash
pip install torch gymnasium flappy-bird-gymnasium numpy pygame
```

Run the project using the Python entry-point file after completing the required setup.

## Author

Developed as a hands-on project to explore Reinforcement Learning and Deep Learning using Python and PyTorch.
