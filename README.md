# AI Reinforcement Learning with CartPole

This project implements a Deep Q-Network (DQN) agent that learns to balance a pole on a cart using reinforcement learning techniques. The agent is trained in the classic CartPole environment from OpenAI's Gym library.

![CartPole Environment](https://gymnasium.farama.org/_images/cart_pole.gif)

## Project Overview

This project demonstrates:

- Fundamentals of reinforcement learning
- Building and training neural networks with Keras
- Creating a DQN agent using Keras-RL2
- Training an agent to solve the CartPole balancing problem
- Saving and loading trained models

## Prerequisites

- Python 3.8
- Basic understanding of neural networks and reinforcement learning concepts

## Dependencies

The following libraries are required with specific versions:

```
gym==0.25.2
keras==2.10.0
keras-rl2==1.0.5
tensorflow==2.3.0
numpy==1.18.5
protobuf==3.20.0
```

## Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/AI-Reinforcement-Learning.git
cd AI-Reinforcement-Learning
```

## Running the Project

### Recommended: Using VSCode with Jupyter Extension

1. Install Visual Studio Code from [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Install the Jupyter extension for VSCode
3. Open the project folder in VSCode
4. Open the `Reinforcement Learning.ipynb` notebook file
5. Run the cells sequentially to see the agent learn and perform

## Project Structure

- `Reinforcement Learning.ipynb`: Main Jupyter notebook containing all code and explanations
- `dqn_weights.h5f`: Saved model weights for the trained agent
- `checkpoint`: TensorFlow checkpoint file

## What You'll Learn

- Fundamental concepts of AI and reinforcement learning
- How to set up and interact with environments in OpenAI Gym
- Building neural network architectures with Keras
- Creating and training DQN agents
- Testing and visualizing agent performance
- Saving and loading model weights

## Key Components

1. **Environment Setup**: Initializing the CartPole environment
2. **Model Building**: Creating a neural network with Keras
3. **Agent Creation**: Implementing a DQN agent with Keras-RL2
4. **Training**: Teaching the agent to balance the pole
5. **Testing**: Visualizing the agent's performance
6. **Model Persistence**: Saving and loading trained weights

## Credits

This project is based on Nicholas Renotte's workshop on Deep Learning, which this repo serves to maintain for future learners. The original workshop can be found at [YouTube - Nicholas Renotte](https://www.youtube.com/watch?v=cO5g5qLrLSo).
