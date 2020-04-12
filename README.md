# Reinforcement Learning at MVA

This repository contains 5 notebooks done at the MVA master (2019) in the field of Reinforcement Learning. 

The notebook entitled Q_Learning can be seen as a brief introduction to Reinforcement Learning, gathering an implementation of the Value Iteration algorithm and the Q-learning algorithm (for finite MDPs).

Linear_bandits is an exploration in linear bandits, where two strategies are implemented and compared: the OFUL (Optimism in the Face of Uncertainty) strategy and the Thomson Sampling strategy.

As suggested by its name, DQN_from_scratch contains an implementation of a Deep Q-Network from scratch. Particular attention is paid to the deep network (implemented in keras) and its structure. WARNING: the videos do not work on Firefox, prefer Google Chrome.

The notebook Optimistic_planning tackles the issue of exploration in finite-horizon tabular MDPs. An implementation of the UCB-VI algorithm can be found, as well as a comparison of its performance with the Hoeffding's and the Bernstein's bounds. 

The notebook Policy_gradients, also entitled Reinforcement Learning with function approximation, was developed in pytorch and is based on the cartpole-v1 example from the Open-AI gym library. An implementation of the REINFORCE, batched gradient and Advantage Actor Critic algorithms can be found.

For time considerations, these notebooks can be run on Google Colab.
