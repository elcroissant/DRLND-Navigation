# Learning Algorithm

Two algorithms have been used for comparison:
1) Deep Q-learning (for details go to: https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf)
2) Double-Deep Q-learning (for details go to: https://arxiv.org/abs/1509.06461)
Deep Q-Learning tends to overestimate action values. 
Double Q-Learning has been shown to work well in practice to help with this.

# Plot of Rewards
1) Deep Q-learning

2) Double-Deep Q-learning

# Ideas for Future Work
- Prioritized Experience Replay (for details go to: https://arxiv.org/abs/1511.05952)
- Dueling DQN (for details go to: https://arxiv.org/abs/1511.06581)
- Learning from multi-step bootstrap targets (for details go to: https://arxiv.org/abs/1602.01783)
- Distributional DQN (for details go to: https://arxiv.org/abs/1707.06887)
- Noisy DQN (for details go to: https://arxiv.org/abs/1706.10295)

Researchers at Google DeepMind recently tested the performance of an agent that incorporated all six of these modifications including 5 above and DDQN. The corresponding algorithm was termed Rainbow. (for details go to: https://arxiv.org/abs/1710.02298)
