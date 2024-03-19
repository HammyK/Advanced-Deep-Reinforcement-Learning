### Overview 
This repository contains code and reports for implementing reinforcement learning algorithms, specifically Deep Q-Network (DQN) and Proximal Policy Optimization (PPO), applied to the Space Invaders environment using OpenAI Gym and RLlib libraries.

#### Contents

- `DRL_Advanced_DQN.ipynb`: Jupyter Notebook containing implementation and analysis of the DQN algorithm for Space Invaders.
- `DRL_Advanced_PPO.ipynb`: Jupyter Notebook containing implementation and analysis of the PPO algorithm for Space Invaders.
- `Space Invaders Report.pdf`: Report summarizing the implementation, results, and analysis of both DQN and PPO algorithms applied to Space Invaders.

### About Space Invaders Reinforcement Learning
In this project, we aim to train a reinforcement learning agent to play the Space Invaders game autonomously using the Atari learning environment provided by OpenAI Gym and RLlib libraries.

#### Deep Q-Network (DQN) Algorithm
We start by implementing the DQN algorithm, which combines Q-learning with convolutional neural networks (CNN) and experience replay. This algorithm is well-suited for complex environments with large state spaces, as it requires less memory compared to traditional Q-table methods.

#### Proximal Policy Optimization (PPO) Algorithm

Following DQN, we also apply the PPO algorithm, which is a policy gradient optimization algorithm. PPO adjusts its policy at each step to improve certain parameters while ensuring consistency with the previous policy. It utilizes actor-critic networks and is widely used in reinforcement learning scenarios.

### Implementation Details

- **Random Policy Experimentation**: Initial experiments involve running the agent with a random policy to observe random scores over multiple episodes.
- **Hyperparameter Tuning**: We perform hyperparameter tuning for both DQN and PPO algorithms to improve performance. This includes tuning parameters such as activation functions, learning rates, and network architectures.
- **Analysis and Visualization**: Results from training episodes are analyzed and visualized using tools like TensorBoard to track learning progress and identify areas for improvement.

### Instructions for Use

- Clone this repository to your local machine.
- Open and run the Jupyter Notebooks (`DRL_Advanced_DQN.ipynb` and `DRL_Advanced_PPO.ipynb`) in your preferred environment (e.g., Google Colab, JupyterLab).
- Follow the instructions provided within the notebooks to train and evaluate the DQN and PPO agents.
- Refer to the `Space Invaders Report.pdf` for a detailed analysis of the results and insights gained from the experiments.

## Additional Notes

- Further experimentation and parameter tuning may be conducted to improve the performance of the agents.
- Suggestions for future improvements or alternative algorithms are welcome.

Thank you for your interest in this project! If you have any questions or feedback, feel free to reach out to the project contributors.
