### Conclusions

The performance metrics and training data provide a comprehensive view of the system's behavior and efficacy. 

1. **Rollout Metrics**:
   - The average episode length of 1000 steps and an average reward of 28.5 indicate that the system is performing consistently over extended periods.
   - The simulation runs efficiently at 184 frames per second, completing 334 iterations in a total time of 5445 seconds, covering 1,002,000 timesteps.

2. **Training Metrics**:
   - The approximate KL divergence of 0.0144 and a clip fraction of 0.143 with a clip range of 0.2 suggest that the policy updates are stable and within expected bounds.
   - The entropy loss of -1.68 indicates a moderate level of exploration.
   - An explained variance of 0.481 implies that the model's predictions account for nearly half of the variance in the rewards.
   - The learning rate of 0.0001 and a low overall loss of 0.0331 demonstrate that the training process is well-tuned and effective.
   - The policy has been updated 3330 times, with a policy gradient loss of -0.0173, indicating incremental improvements in the policy.
   - A standard deviation of 0.561 and a value loss of 0.148 are within acceptable ranges, suggesting that the value function is learning appropriately.

3. **Episode Performance**:
   - The episode returns and costs exhibit significant variability, with the highest return being 42.323 and the lowest being -12.466.
   - The costs also fluctuate, with the highest cost being 753.000 and the lowest cost being 0.000.
   - Despite some episodes with negative returns and high costs, the majority of episodes show positive returns and manageable costs, indicating overall stability and effectiveness of the policy.
  


In summary, the system shows consistent performance with stable training metrics and generally positive returns across episodes. While there are occasional high costs and negative returns, the overall trend is positive, suggesting that the policy is effective and the training process is well-optimized. Future efforts should focus on reducing variability and addressing episodes with high costs to further enhance performance.

[CarButton1 (4).webm](https://github.com/Naveed776/Safe_expolration_RL_SafetyGym/assets/91262613/cf9be641-4a89-43af-b21f-37299e647f17)


![CarButton1](https://github.com/Naveed776/Safe_expolration_RL_SafetyGym/assets/91262613/1d7f4dd1-f946-440d-bec3-c50831b1d49b)
