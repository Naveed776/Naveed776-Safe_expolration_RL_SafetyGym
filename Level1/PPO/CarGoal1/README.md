### Conclusions

The performance and training metrics indicate that the system is functioning efficiently and effectively.

1. **Rollout Metrics**:
   - The average episode length of 1000 steps with an average reward of 40.9 demonstrates consistent performance.
   - The simulation operates at 283 frames per second, with 334 iterations completed in 3533 seconds, covering 1,002,000 total timesteps, highlighting its efficiency.

2. **Training Metrics**:
   - The approximate KL divergence of 0.0086 and a clip fraction of 0.0902 within a clip range of 0.2 suggest stable and controlled policy updates.
   - The entropy loss of -2.15 indicates a good level of exploration.
   - An explained variance of 0.318 implies moderate accuracy in the model's predictions.
   - The low learning rate of 0.0001 and an overall loss of 0.0174 show effective training.
   - The policy gradient loss of -0.0101 and a standard deviation of 0.71 are within acceptable ranges, indicating incremental policy improvements and appropriate learning.
   - A value loss of 0.138 suggests the value function is learning well.

3. **Episode Performance**:
   - The returns are generally positive, with the highest return being 46.353 and the lowest being 34.786.
   - The costs vary, with some episodes incurring zero cost and others having higher costs up to 213.000.
   - Despite some episodes with higher costs, the overall trend of returns is positive, indicating stability and effectiveness of the policy.

In summary, the system exhibits strong performance with stable training metrics and consistently positive episode returns. The variability in costs suggests areas for potential optimization, but the overall effectiveness and efficiency of the policy are evident. Future efforts should focus on reducing cost variability to further enhance system performance.


[CarGoal1.webm](https://github.com/Naveed776/Safe_expolration_RL_SafetyGym/assets/91262613/6225c866-4a3e-4242-97a9-da7344aa2744)

![CarGoal1](https://github.com/Naveed776/Safe_expolration_RL_SafetyGym/assets/91262613/abde9373-fe4b-4af7-a7ed-bb780a3b90a0)
