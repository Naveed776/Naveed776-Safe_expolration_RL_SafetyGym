**Training Summary**

The training process achieved a frame rate of 384 fps over 34 iterations, totaling 265 seconds and reaching 102,000 timesteps. Key training metrics included an approximate KL divergence of 0.0048, a clip fraction of 0.0546, a clip range of 0.2, and an entropy loss of -2.76. The explained variance was 0.131, with a learning rate of 0.0001. The model experienced a loss of -0.0131 over 330 updates, with a policy gradient loss of -0.00817, a standard deviation of 0.96, and a value loss of 0.0134.

**Episode Performance**

Episode returns and costs varied widely, with the highest return being 4.648 and the lowest being -0.278. Costs ranged from 0.000 to 541.000. Notable episodes include:
- Episode 1: Return 1.593, Cost 425.000
- Episode 3: Return 0.441, Cost 541.000
- Episode 5: Return 3.223, Cost 198.000
- Episode 22: Return 4.648, Cost 0.000
- Episode 23: Return 4.124, Cost 211.000

**Conclusion**

The training session demonstrated high performance, achieving 102,000 timesteps in 265 seconds at 384 fps over 34 iterations. The key training metrics indicated a good fit with minimal policy gradient and value losses. Episode performance showed variability in returns and costs, suggesting areas for optimization in return consistency and cost management. Overall, the training yielded promising results with potential for further improvement.

[Screencast from 07-06-2024 03:53:20 PM.webm](https://github.com/Naveed776/Safe_expolration_RL_SafetyGym/assets/91262613/a811cd6c-2086-436c-9526-c35721d4ab33)

![Figure_1](https://github.com/Naveed776/Safe_expolration_RL_SafetyGym/assets/91262613/32d159de-dfad-41d2-8b33-0f40cc7fd741)


