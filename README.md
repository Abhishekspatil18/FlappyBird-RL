# Flappy Bird AI — Deep Reinforcement Learning

## Overview
This project explores training an AI agent to play Flappy Bird using Deep Q-Network (DQN), a reinforcement learning algorithm.

## Key Components
- **DQN:** Estimates action values using a neural network.
- **Agent:** Manages action selection and the learning process.
- **Experience Replay:** Stores previous experiences for training.
- **Game Environment:** Provides the Flappy Bird gameplay interaction.
- **Training Configuration:** Stores configurable parameters in a YAML file.

## Technologies
- Python
- PyTorch or the deep learning framework used in this implementation
- Pygame, if used by the game environment
- NumPy
- PyYAML

## Project Structure
```text
FlappyBird-RL/
├── agent.py
├── dqn.py
├── experience_replay.py
├── game_flappy_bird.py
├── parameters.yaml
├── requirements.txt
├── .gitignore
└── README.md
```

## Getting Started
1. Install Python and the dependencies listed in `requirements.txt`.
2. Review the training configuration in `parameters.yaml`.
3. Follow the entry-point and execution instructions after verifying the project's code.

## Learning Concepts
- Deep Q-Learning
- Experience Replay
- Exploration versus exploitation
- Neural-network-based action-value estimation

## Reference
Inspired by the [RL_DQN repository](https://github.com/shradha-khapra/RL_DQN).

This project should credit the original authors for any code or material adapted from their work. Please refer to the original repository's license for reuse conditions.
