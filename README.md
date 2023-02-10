# Approximate-RL-Methods-for-CartPole-Environment-on-OpenAI-gym
In tabular reinforcement learning methods which broadly includes dynamic programming, Monte-Carlo simulation methods and temporal difference methods (Q-learning, SARSA e.t.c), the state (V(s)) and state-action (Q(s,a)) values were stored in tables.  
These methods are practical for simple and discrete environments, but when the states of the environment is continuous and/or very large, the tabular methods are limited.
Quite frankly, most of our real-world environments are not discrete so approximate RL methods are developed to cater for these scenerios.
Approximate RL methods use supervised machine learning (traditional and deep learning) methods to approximate the state-action values.
In this repo, linear models (linear regression) is combined with RL methods (Q-learning and Monte-carlo) to approximate the state-action values, feature engineering (RBF) model is used to make the linear model approximate non-linear functions and applied to the cartpole environment in open-AI gym.
Batch gradient descent with Monte Carlo is also applied to the cartpole environment in this repo.
