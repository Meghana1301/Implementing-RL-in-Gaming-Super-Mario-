# Implementing-RL-in-Gaming-Super-Mario-
# Training a Mario Agent with Reinforcement Learning
# Overview
The goal of this project is to train an AI agent to play Super Mario Bros using reinforcement learning techniques. The agent learns to navigate the game environment, avoid obstacles, and reach the goal autonomously. We utilize the Double Deep Q-Network (DDQN) algorithm to train the agent, which is well-suited for environments with discrete action spaces.

# Prerequisites:
Python 3.x<br>
PyTorch<br>
NumPy<br>
Gym Super Mario Bros<br>
nes-py<br>
skimage<br>

To install the required dependencies, run:<br>
pip install -r requirements.txt

# Usage:
Clone the repository:<br>
bash<br>
git clone https://github.com/yourusername/Reinforcement-Learning-for-Super-Mario-Bros.git<br>
Navigate to the project directory:<br>
bash<br>
cd Reinforcement-Learning-for-Super-Mario-Bros<br>
Run the main script to train the DDQN agent:<br>
css<br>
python main.py<br>

# Code Structure:
main.py: Contains the main logic for training the DDQN agent.<br>
utils.py: Utility functions used in the training process.<br>
checkpoints/: Directory to save trained DDQN models.<br>

# Customization:
You can customize the following parameters in main.py:<br>

Number of training episodes<br>
Dimensionality of the action and state spaces<br>
Exploration rate decay<br>
Learning rate<br>
Batch size<br>
Discount factor (gamma)<br>

# Results:
During training, monitor the console output for the agent's performance metrics. Once training is complete, evaluate the trained agent's gameplay in the game environment.

<img src="https://github.com/Meghana1301/Implementing-RL-in-Gaming-Super-Mario-/blob/main/mario.png" alt="Girl in a jacket" width="500" height="600">

