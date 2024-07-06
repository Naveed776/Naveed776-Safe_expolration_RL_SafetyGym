# Comparison of Car Button PPO and Car Button PPO Lagrangian

## 1. Time to Converge

**Car Button PPO**:
- FPS: 208
- Total Timesteps: 102,000
- Time Elapsed: 488 seconds

**Car Button PPO Lagrangian**:
- FPS: 264
- Total Timesteps: 102,000
- Time Elapsed: 384 seconds

**Analysis**: Car Button PPO Lagrangian converges faster due to a higher FPS and lower total time elapsed.

## 2. Policy Safety

**Car Button PPO**:
- Average Episode Cost: Variable, with several episodes having costs above 200.
- Lowest Episode Cost: 0 (Episodes 20 and 26)
- Highest Episode Cost: 514 (Episode 21)

**Car Button PPO Lagrangian**:
- Average Episode Cost: Lower, with many episodes having costs below 200.
- Lowest Episode Cost: 0 (Episodes 17 and 23)
- Highest Episode Cost: 284 (Episode 2)

**Analysis**: Car Button PPO Lagrangian appears to have generally lower and more consistent episode costs, indicating better policy safety.

## 3. Performance Metrics

**Car Button PPO**:
- Average Return: ~11 (over 30 episodes)
- Approx. KL: 0.0065225437
- Clip Fraction: 0.0519
- Explained Variance: 0.335
- Policy Gradient Loss: -0.00978
- Value Loss: 0.0135

**Car Button PPO Lagrangian**:
- Average Return: ~3 (over 30 episodes)
- Approx. KL: 0.006562297
- Clip Fraction: 0.0718
- Explained Variance: 0.39
- Policy Gradient Loss: -0.00952
- Value Loss: 0.0386

**Analysis**: While Car Button PPO achieves a higher average return, Car Button PPO Lagrangian shows slightly better explained variance, indicating potentially better model performance in estimating value functions. However, the higher value loss in PPO Lagrangian suggests more variability in performance.

## Summary

- **Time to Converge**: Car Button PPO Lagrangian converges faster.
- **Policy Safety**: Car Button PPO Lagrangian exhibits better safety with lower and more consistent episode costs.
- **Performance Metrics**: Car Button PPO achieves higher average returns, but Car Button PPO Lagrangian demonstrates slightly better explained variance and faster convergence, albeit with higher value loss.



## Comparison of CAR GOAL PPO and CAEGOAL PPO Lagrangian

### 1. Time to Converge

**CAR GOAL PPO**:
- FPS: 310
- Total Timesteps: 102,000
- Time Elapsed: 328 seconds

**CAEGOAL PPO Lagrangian**:
- FPS: 384
- Total Timesteps: 102,000
- Time Elapsed: 265 seconds

**Analysis**: CAEGOAL PPO Lagrangian converges faster with a higher FPS and lower total time elapsed.

### 2. Policy Safety

**CAR GOAL PPO**:
- Average Episode Cost: Variable, with some episodes having costs exceeding 700.
- Lowest Episode Cost: 0 (multiple episodes)
- Highest Episode Cost: 769 (Episode 30)

**CAEGOAL PPO Lagrangian**:
- Average Episode Cost: Variable, with some episodes having costs above 400.
- Lowest Episode Cost: -0.220 (Episode 4)
- Highest Episode Cost: 541 (Episode 3)

**Analysis**: CAEGOAL PPO Lagrangian shows variability in episode costs similar to CAR GOAL PPO but generally with lower maximum costs.

### 3. Performance Metrics

**CAR GOAL PPO**:
- Average Return: ~12 (over 30 episodes)
- Approx. KL: 0.005560862
- Clip Fraction: 0.0609
- Explained Variance: 0.451
- Policy Gradient Loss: -0.00755
- Value Loss: 0.019

**CAEGOAL PPO Lagrangian**:
- Average Return: ~1.8 (over 30 episodes)
- Approx. KL: 0.0048481915
- Clip Fraction: 0.0546
- Explained Variance: 0.131
- Policy Gradient Loss: -0.00817
- Value Loss: 0.0134

**Analysis**: CAR GOAL PPO achieves a significantly higher average return compared to CAEGOAL PPO Lagrangian. It also demonstrates better explained variance and lower value loss.

### Summary

- **Time to Converge**: CAEGOAL PPO Lagrangian converges faster than CAR GOAL PPO.
- **Policy Safety**: Both algorithms show variability in episode costs, but CAEGOAL PPO Lagrangian generally has lower maximum costs.
- **Performance Metrics**: CAR GOAL PPO outperforms CAEGOAL PPO Lagrangian in terms of average return, explained variance, and value loss, indicating better overall performance in policy optimization.



## Comparison of Point Button PPO and Point Button PPO Lagrangian

### 1. Time to Converge

**Point Button PPO**:
- FPS: 267
- Total Timesteps: 102,000
- Time Elapsed: 381 seconds

**Point Button PPO Lagrangian**:
- FPS: 282
- Total Timesteps: 102,000
- Time Elapsed: 361 seconds

**Analysis**: Point Button PPO Lagrangian converges slightly faster with a higher FPS and lower total time elapsed.

### 2. Policy Safety

**Point Button PPO**:
- Average Episode Cost: Variable, with some episodes having costs exceeding 300.
- Lowest Episode Cost: 13.181 (Episode 1)
- Highest Episode Cost: 24.738 (Episode 11)

**Point Button PPO Lagrangian**:
- Average Episode Cost: Variable, with some episodes having costs above 250.
- Lowest Episode Cost: 1.859 (Episode 15)
- Highest Episode Cost: 19.500 (Episode 13)

**Analysis**: Both algorithms show variability in episode costs, with Point Button PPO Lagrangian generally showing lower maximum costs.

### 3. Performance Metrics

**Point Button PPO**:
- Average Return: ~18.2 (over 25 episodes)
- Approx. KL: 0.004174143
- Clip Fraction: 0.0379
- Explained Variance: 0.819
- Policy Gradient Loss: -0.00626
- Value Loss: 0.0373

**Point Button PPO Lagrangian**:
- Average Return: ~8.1 (over 25 episodes)
- Approx. KL: 0.0075296415
- Clip Fraction: 0.0807
- Explained Variance: 0.669
- Policy Gradient Loss: -0.00825
- Value Loss: 0.0546

**Analysis**: Point Button PPO achieves a significantly higher average return compared to Point Button PPO Lagrangian. It also demonstrates better explained variance and lower value loss.

### Summary

- **Time to Converge**: Point Button PPO Lagrangian converges slightly faster than Point Button PPO.
- **Policy Safety**: Both algorithms show variability in episode costs, but Point Button PPO Lagrangian generally has lower maximum costs.
- **Performance Metrics**: Point Button PPO outperforms Point Button PPO Lagrangian in terms of average return, explained variance, and value loss, indicating better overall performance in policy optimization.


## Comparison of PointGoal PPO and PointGoal PPO Lagrangian

### 1. Time to Converge

**PointGoal PPO**:
- FPS: 440
- Total Timesteps: 102,000
- Time Elapsed: 231 seconds

**PointGoal PPO Lagrangian**:
- FPS: 473
- Total Timesteps: 102,000
- Time Elapsed: 215 seconds

**Analysis**: PointGoal PPO Lagrangian converges faster with a higher FPS and shorter total time elapsed.

### 2. Policy Safety

**PointGoal PPO**:
- Average Episode Cost: Variable, with some episodes having costs exceeding 200.
- Lowest Episode Cost: 18.201 (Episode 10)
- Highest Episode Cost: 25.887 (Episode 20)

**PointGoal PPO Lagrangian**:
- Average Episode Cost: Variable, with some episodes having costs above 200.
- Lowest Episode Cost: 4.866 (Episode 23)
- Highest Episode Cost: 17.012 (Episode 3)

**Analysis**: Both algorithms show variability in episode costs, with PointGoal PPO Lagrangian showing a significantly lower minimum cost.

### 3. Performance Metrics

**PointGoal PPO**:
- Average Return: ~21.4 (over 25 episodes)
- Approx. KL: 0.004891158
- Clip Fraction: 0.0682
- Explained Variance: 0.593
- Policy Gradient Loss: -0.00574
- Value Loss: 0.0416

**PointGoal PPO Lagrangian**:
- Average Return: ~9.0 (over 25 episodes)
- Approx. KL: 0.0044182055
- Clip Fraction: 0.0458
- Explained Variance: 0.771
- Policy Gradient Loss: -0.00489
- Value Loss: 0.0291

**Analysis**: PointGoal PPO achieves a significantly higher average return compared to PointGoal PPO Lagrangian. However, PointGoal PPO Lagrangian demonstrates better explained variance and lower value loss.

### Summary

- **Time to Converge**: PointGoal PPO Lagrangian converges faster than PointGoal PPO.
- **Policy Safety**: Both algorithms show variability in episode costs, but PointGoal PPO Lagrangian generally shows a lower minimum cost.
- **Performance Metrics**: PointGoal PPO achieves a higher average return, while PointGoal PPO Lagrangian performs better in terms of explained variance and value loss.





### Conclusion

The comparisons between various variants of Car Button PPO and Car Button PPO Lagrangian, as well as their counterparts in different scenarios, highlight significant differences in convergence speed, policy safety, and performance metrics.

**Time to Converge**: Across all comparisons, PPO Lagrangian consistently demonstrates faster convergence times compared to its respective PPO counterpart. This is attributed to higher frames per second (FPS) and lower total elapsed time, indicating efficiency in learning and optimizing policies.

**Policy Safety**: PPO Lagrangian tends to exhibit better policy safety with lower and more consistent episode costs compared to standard PPO. This suggests improved stability in the learned policies and potentially fewer high-cost outliers.

**Performance Metrics**: While standard PPO often achieves higher average returns, PPO Lagrangian shows strengths in other metrics such as explained variance and sometimes lower value loss. This indicates that PPO Lagrangian may offer more reliable estimates of value functions and improved policy optimization in certain contexts.

In summary, while each variant shows strengths in different aspects, PPO Lagrangian consistently emerges as a favorable choice due to its faster convergence and improved policy safety. However, the selection between these variants should also consider specific application requirements and trade-offs in performance metrics. Below is a consolidated table summarizing the key comparisons:

| Comparison                      | Time to Converge     | Policy Safety                               | Performance Metrics                               |
|---------------------------------|----------------------|---------------------------------------------|---------------------------------------------------|
| Car Button PPO vs. PPO Lagrangian | PPO Lagrangian faster | PPO Lagrangian has lower and more consistent episode costs | PPO achieves higher average return; PPO Lagrangian better explained variance, higher value loss |
| CAR GOAL PPO vs. PPO Lagrangian | PPO Lagrangian faster | Similar variability in episode costs; PPO Lagrangian generally lower maximum costs | PPO achieves higher average return, better explained variance, lower value loss |
| Point Button PPO vs. PPO Lagrangian | PPO Lagrangian slightly faster | PPO Lagrangian generally lower maximum costs | Point Button PPO achieves higher average return, better explained variance, lower value loss |
| PointGoal PPO vs. PPO Lagrangian | PPO Lagrangian faster | PPO Lagrangian generally lower minimum cost | PointGoal PPO achieves higher average return; PPO Lagrangian better explained variance, lower value loss |

These comparisons underscore the nuanced advantages of PPO Lagrangian in enhancing efficiency and stability in reinforcement learning tasks, suggesting its potential suitability for applications where faster convergence and improved policy safety are paramount.
