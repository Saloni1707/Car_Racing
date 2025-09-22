Car Racing with Deep Q-Learning (DQN)

This project is a simulation where a car learns to drive using Reinforcement Learning (RL) powered by the Deep Q-Network (DQN) approach. The goal is to minimize collisions while improving driving performance over time.

Implemented DQN using both the current neural network and the target neural network, addressing the drawbacks of classical Q-learning. Since RL problems often involve a very large state space, DQN proves to be a powerful and efficient solution.</br>

Throughout this project, explored several concepts in RL and DQN, deepened my understanding of neural networks in control systems, and learned from various resources.

I.Project Structure

Reinforcement_Learning → Contains the main logic of the DQN, including how the agent selects actions and updates its Q-values.</br>

Car_spec → Contains the car’s mathematical model, physics, and configuration details.

II.Learnings

1.Why Q-learning struggles in large state spaces.</br>
2.How experience replay and target networks improve training stability.</br>
3.Practical implementation of RL in a continuous, dynamic environment.

References</br>
[Karpathy’s blog on Reinforcement Learning](https://karpathy.github.io/2016/05/31/rl/)(interesting to read)</br>
[Good video for DQN](https://youtu.be/EUrWGTCGzlA?si=HSKi0gqU7_qrdCJ8)(an overview)
