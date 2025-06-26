# Deep Q-Learning for Treasure Hunt Game – CS-370 Current/Emerging Trends in Computer Science

### Project Overview 
This project explores the implementation of a reinforcment learning-based intelligent agent–represented by a pirate–tasked with navigating a maze to locate a hidden treasure. Using Q-learning, the pirate learns optimal strategies to maximize reward and minimize penalties over repeated episodes of interaction with its environment.

The core objective of this work was to implement and train an intelligent agent capable of decision-making through trial-and-error learning, utilizing neural neural networks to estimate the expected utility (Q-values) of taking particular actions in specific states. 

### Code Contributions 
#### *Provided Code:*
+ **TreasureMaze.py:** Defined the environment structure, including maze layout, starting position, and treasure location. It served as the foundation for modeling the agent's interaction space.
+ **GameExperience.py:** Handles the storage of experience replay data(episodes), crucial for training the reinforcement learning model.
+ **Jupter notebook framwork:** Contained the environment setup, visualizations, and placeholders for model training logic.

### Code Developed Independently
+ Implemented the Deep Q-Network (DQN) architecture using Keras, including input, hidden, and output layers appropriate for the maze environment.
+ Developed the action-selection logic using an epsilon-greedy strategy to balance exploration and exploitation.
+ Implemented the *remember()*,*replay()*, and "train()* functions to enable the agent to learn from its experiences and update its policy accordingly.
+ Conducted multiple training episodes to iteratively refine the agent's decision-making capabilities through reward-based learning.

## Connection to Computer Science 
