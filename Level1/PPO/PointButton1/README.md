### Conclusion

The system demonstrates strong performance and efficiency. The average episode length is 1000 steps, with an average reward of 38.1. The simulation runs at 215 frames per second, completing 334 iterations in 4657 seconds, covering 1,002,000 timesteps.

Training metrics show effective learning:
- Low approximate KL divergence (0.0092) and clip fraction (0.105) indicate stable policy updates.
- An entropy loss of -2.13 suggests a good level of exploration.
- The explained variance of 0.584 shows moderate prediction accuracy.
- The learning rate (0.0001) and loss (0.0362) values indicate well-tuned training.
- The policy gradient loss of -0.0119 and standard deviation of 0.705 are within acceptable ranges, showing incremental policy improvements.
- Value loss of 0.155 is appropriate for the training process.

Episode performance shows variability in returns and costs:
- Returns range from 30.727 to 51.325, with the highest return being 51.325.
- Costs range from 71.000 to 342.000, indicating areas for potential optimization.

Overall, the system is effective, with consistent performance and stable training metrics. Future efforts should focus on reducing cost variability to further enhance the system's performance.

[PointButton1.webm](https://github.com/Naveed776/Safe_expolration_RL_SafetyGym/assets/91262613/ed0a9e47-0499-402a-ae23-1f1f67b0f7c6)


![PointButton1](https://github.com/Naveed776/Safe_expolration_RL_SafetyGym/assets/91262613/6a037f38-83dd-4839-abf5-e19c594896a1)
