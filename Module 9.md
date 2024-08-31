## Resampling
1. We want to use the Monte Carlo method to estimate the probability of getting exactly one ace (one spot) in three rolls of die.

Which of the following is a correct description for doing this?
> To simulate three rolls of a die, we draw three times a number at random (with replacement) from 1,2,3,4,5,6.  If we get the number `1' exactly once, then we label this trial to be a success. We repeat this B=1000 times. The proportion of successes in these 1000 trials is our Monte Carlo estimate of the probability in question.
2. We want to use the Monte Carlo Method to approximate the standard error of our estimate from Question 1.

Which of the following is a correct description for doing this?
> We repeat the whole Monte Carlo simulation done in Question 1 many times (e.g. 2000 times). Each time we get an estimate of the probability in question. We compute the standard deviation of these 2000 estimates.
3. We want to use the bootstrap to estimate the bias of θ:
![image](https://github.com/user-attachments/assets/842ef187-9df6-43f2-8cb9-b83a993f0660)
 

> ![image](https://github.com/user-attachments/assets/bc26612f-040b-456f-817b-38122785eea1)
4. We want to compute a 90% bootstrap percentile interval for the correlation coefficient based on 32 pairs
![image](https://github.com/user-attachments/assets/740259b0-7a21-4e79-b9c9-6d6ceed8143d)
> ![image](https://github.com/user-attachments/assets/0f4b4f15-00c8-4343-bb48-b954da589ec2)
