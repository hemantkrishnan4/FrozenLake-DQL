# FrozenLake-DQL

FrozenLake-DQL is a reinforcement learning project that applies Deep Q-Learning to the FrozenLake environment using PyTorch. The project utilizes a neural network to learn a policy that allows an agent to navigate the FrozenLake map successfully.



![FrozenLake](https://github.com/hemantkrishnan4/FrozenLake-DQL/assets/96692095/2d6bcdfb-7742-4eb9-b94e-d63a5da864eb)





# Gymnasium Reinforcement Learning

Gymnasium Reinforcement Learning is a collection of Python code that solves Reinforcement Learning environments from the Gymnasium Library, formerly OpenAI’s Gym library.


## Introduction

This project implements Deep Q-Learning (DQL) on the FrozenLake environment, a classic problem in reinforcement learning. The agent learns to make decisions by interacting with the environment, and the training process involves updating a neural network based on the experiences gained during exploration.

## Prerequisites

Make sure you have the following installed before running the project:

- Python (>=3.6)
- [PyTorch](https://pytorch.org/)
- [Gym](https://gym.openai.com/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/hemantkrishnan4/FrozenLake-DQL.git
   cd FrozenLake-DQL
   ```
The Gymnasium Library is supported on Linux and Mac OS. On Windows, there may be issues with the Box2D package, leading to errors during installation. If you encounter errors like the following:

ERROR: Failed building wheels for box2d-py
ERROR: Command swig.exe failed
ERROR: Microsoft Visual C++ 14.0 or greater is required.
