### Conclusion

The system performs efficiently with an average episode length of 1000 steps and achieves a commendable average reward of 35.6. Operating at a high frame rate of 414 frames per second, it completes 334 iterations over 2416 seconds, accumulating a total of 1,002,000 timesteps.

Key training metrics highlight stable performance and effective learning:
- **Approximate KL Divergence:** 0.0123, indicating controlled policy updates.
- **Clip Fraction:** 0.113 within a clip range of 0.2, ensuring stable policy adjustments.
- **Entropy Loss:** -2.78, supporting sufficient exploration during training.
- **Explained Variance:** 0.557, suggesting accurate predictions.
- **Learning Rate:** 0.0001, with a low loss of 0.0365, demonstrating efficient learning.
- **Policy Gradient Loss:** -0.00647 and Standard Deviation of 0.975, indicating consistent policy adjustments.
- **Value Loss:** 0.0938, reflecting effective learning of the value function.

Episode returns vary between 33.489 and 38.399, showcasing variability but generally positive outcomes.

In summary, the system exhibits robust performance with stable training dynamics and effective learning strategies. The variability in episode returns suggests ongoing optimization opportunities to further enhance average rewards and reduce return fluctuation.

[Level1_Unconstrained_PointGoal1_PointGoal.webm](https://github.com/Naveed776/Safe_expolration_RL_SafetyGym/assets/91262613/7c7fd630-66ef-4392-bf35-de93334367d7)

![PointGoal](https://github.com/Naveed776/Safe_expolration_RL_SafetyGym/assets/91262613/b9f10efe-b9dd-4cb1-896b-6f2abf686474)


