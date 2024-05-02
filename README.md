# Implementing-RL-in-Gaming-Super-Mario-
# Training a Mario Agent with Reinforcement Learning
# Overview
The goal of this project is to train an AI agent to play Super Mario Bros using reinforcement learning techniques. The agent learns to navigate the game environment, avoid obstacles, and reach the goal autonomously. We utilize the Double Deep Q-Network (DDQN) algorithm to train the agent, which is well-suited for environments with discrete action spaces.

# Prerequisites:
Python 3.x
PyTorch
NumPy
Gym Super Mario Bros
nes-py
skimage

To install the required dependencies, run:
pip install -r requirements.txt

# Usage:
Clone the repository:
bash
git clone https://github.com/yourusername/Reinforcement-Learning-for-Super-Mario-Bros.git
Navigate to the project directory:
bash
cd Reinforcement-Learning-for-Super-Mario-Bros
Run the main script to train the DDQN agent:
css
python main.py

# Code Structure:
main.py: Contains the main logic for training the DDQN agent.
utils.py: Utility functions used in the training process.
checkpoints/: Directory to save trained DDQN models.

# Customization:
You can customize the following parameters in main.py:

Number of training episodes
Dimensionality of the action and state spaces
Exploration rate decay
Learning rate
Batch size
Discount factor (gamma)

# Results:
During training, monitor the console output for the agent's performance metrics. Once training is complete, evaluate the trained agent's gameplay in the game environment.



