# Deep-Reinforcement-Learning-Algorithm-DQN
The project combines reinforcement learning and deep learning


**University at Buffalo - CSE574: Introduction to Machine Learning**
<p>Project 4</p>

### Overview
The project combines reinforcement learning and deep learning. Your task is to teach the agent to navigate
in the grid-world environment. We have modeled Tom and Jerry cartoon, where Tom, a cat, is chasing Jerry,
a mouse. In our modeled game the task for Tom (an agent) is to find the shortest path to Jerry (a goal),
given that the initial positions of Tom and Jerry are deterministic. To solve the problem, we would apply
deep reinforcement learning algorithm - DQN (Deep Q-Network), that was one of the first breakthrough
successes in applying deep learning to reinforcement learning.

### Results
* The solution was able to find the shortest path for Tom (an agent) to Jerry (a goal), given that the initial positions of Tom and Jerry are deterministic in 5000 episodes (~5mins)
* Achieved an average rolling reward of 6 in 10,000 episodes (maximum rank achievable was 8).
* Successfully implemented Deep Q-Network (DQN) using two Atari environments from openAI’s Gym library. 

### Software Used
Python, Keras

### Atari Game Visual
![Atari Game](https://github.com/ravi-teja-sunkara/Deep-Reinforcement-Learning-Algorithm-DQN/blob/master/pong%20AI.jpg)
