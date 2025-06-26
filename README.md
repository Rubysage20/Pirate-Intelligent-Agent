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
+ ###### *What do computer scientists do, and why does it matter?*
- Computer Scientists design and implement algorithms that solve real-world problems efficiently and reliably. They analyze complex systems, develop software, and leverage computational thinking to build intelligent technologies. This work is foundational to innovations in fields such as healthcarem robotics, autonomous systems, and finance. In this project, I applied machine learning principles to train an autonomous agent–a microcosm of how computer science powers intelligent behavior in largers systems.
  
+ ###### *How do I approach problems as a computer scientist?*
- A computer scientist approaches problems with a systematic methodology:
  1. *Problem Decomposition* breaking the problem into solvable components.
  2. *Abstraction* identifying essential details and modeling the system efficiently.
  3. *Algorithmn Design* formulating procedures that produce desired efficiently.
  4. *Evaluation and Iteration* testing and refining solutions using metrics such as accuracy, loss, or convergence rate.
In this project, the problem of pathfinding was abstracted into states and actions, and solved using an iterative learning algorithm (DQN) that required parameter tuning and debugging.

+ ###### *What are my ethical responsibilities to users and organizations?*
- Ethical considerations are essential in developing AI systems. My responsibilities include:
  + *Ensuring Fairness and Safety* AI systems must not produce harmful or biased outcomes. Although this simulation was benigh, similar models in real applications must be carefully audited.
  + *Transparency and Accountability* Clear documentation and explainable models help stakeholders trust and understand AI behavior.
  +  *Respect for Privacy* When applied to real data, privacy must be upheld through secure data handling and anonymization.
this projec, though academic in nature, reinforces the importance of ethical awareness in AI development.

## Reflection
This project synthesized key concepts from machine learning, neural networks, and algorithmic problem-solving. It provided practical experience in designing, implementing, and evaluating an intelligent agent using real-world tools and frameworks. Beyond technical implementation, it emphasized the critical thinking, ethical mindfulness, and system-level design mindset that define the field of computer science.
