# Bandits-in-non-stationary-environments

In this project, we compare the performance of various multi-arm bandit algorithms in different non-stationary settings. Specifically, we empirically evaluate the performance of the EXP3, ϵ-greedy, and Thompson-Sampling algorithms, as well as the discounted and standard variations of UCB. We consider non-stationary environments in the 3-arm bandit scenario whereby the reward distributions of each arm undergo stationary phases interrupted by sudden distribution shifts. Through extensive experiments, we discuss which forms of non-stationarity are favoured by the aforementioned algorithms.

The notebook includes implementations for all the algorithms discussed above. In addition, it includes graphs for the average instantaneous reward and cumulative reward received over time.
