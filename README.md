# DSCI-6612-TEAM-41
Snake Game Using Reinforcement Learning (Q-learning)
# Snake Reinforcement Learning Project Documentation

## Overview

Welcome to the Snake Reinforcement Learning Project! This project implements a snake game environment where the snake learns and adapts its behavior using reinforcement learning (RL) techniques. This document provides a guide for interested students and researchers to understand and use the project.

## Table of Contents

1. [Project Structure](#project-structure)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Usage Instructions](#usage-instructions)
   - [Running the Snake Game](#running-the-snake-game)
   - [Interacting with the Snake](#interacting-with-the-snake)
5. [Customization](#customization)
6. [Training the Neural Network](#training-the-neural-network)
7. [Saving and Loading Models](#saving-and-loading-models)
8. [Evaluation and Metrics](#evaluation-and-metrics)
9. [User Feedback](#user-feedback)
10. [Contributing](#contributing)
11. [License](#license)

## Project Structure

The project is organized as follows:

- `game.py`: Python script defining the snake game environment.
- `snake_agent.py`: Python script implementing the reinforcement learning agent.
- `neural_network.py`: Python script containing the deep neural network architecture.
- `q_learning.py`: Python script with the Q-learning algorithm implementation.
- `trained_model.pth`: Saved trained model file.
- `documentation.md`: Documentation file.

## Requirements

- Python 3.x
- PyTorch (install via `pip install torch`)

## Installation

**1. Clone the repository:**
git clone https://github.com/your-username/snake-reinforcement-learning.git cd snake-reinforcement-learning

**Install dependencies:**
pip install -r requirements.txt

**Usage Instructions**
Running the Snake Game Execute the following command to run the snake game

python game.py

**Interacting with the Snake**
-Use arrow keys for human interaction.
-The RL agent will automatically make decisions based on its training.

**Customization**
-Modify the game.py file to customize the game environment:
-Adjust grid size, snake starting position, and food generation rules.

**Training the Neural Network**
To train the neural network, execute:
 -python neural_network.py

**Saving and Loading Models**
The trained model is saved as trained_model.pth. To load the model in your code:

from neural_network import SnakeNeuralNetwork
model = SnakeNeuralNetwork()
model.load_state_dict(torch.load('trained_model.pth'))

**Evaluation and Metrics**

-Monitor average reward per episode, length of survival, and Q-value function 
 convergence.
-Visualize learning curves for analysis.


**User Feedback**

We welcome your feedback! If you encounter issues or have suggestions, please create an issue.

**Contributing**
Feel free to contribute to the project by forking the repository and submitting pull requests.

