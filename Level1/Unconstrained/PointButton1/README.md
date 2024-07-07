### Conclusion

The system operates with an average episode length of 1000 steps and achieves an average reward of 12.7. Running at 262 frames per second, it completes 34 iterations over 388 seconds, accumulating 102,000 timesteps.

Key training metrics indicate stable performance and effective learning:
- Approximate KL divergence is low at 0.0053, ensuring minimal deviation in policy updates.
- Clip fraction of 0.0533 and a clip range of 0.2 contribute to stable policy updates.
- Entropy loss of -2.75 encourages sufficient exploration during training.
- Explained variance of 0.516 suggests reasonably accurate predictions.
- The learning rate of 0.0001 and low loss of 0.0178 indicate efficient learning.
- Policy gradient loss of -0.00606 and standard deviation of 0.956 show controlled policy adjustments.
- Value loss of 0.0354 reflects effective learning of the value function.

Episode returns vary between 13.181 and 22.446, with individual returns demonstrating variability but generally positive outcomes.

In summary, while the system shows consistent performance and effective learning dynamics, there is room for further optimization to enhance average rewards and reduce return variability across episodes.

[PointButton1.webm](https://github.com/Naveed776/Safe_expolration_RL_SafetyGym/assets/91262613/7c0ddc91-49ce-4b68-81a6-69ae755b6a31)


![PointButton1](https://github.com/Naveed776/Safe_expolration_RL_SafetyGym/assets/91262613/29dea918-5269-4e7b-91ed-3cad2e2a7db3)


