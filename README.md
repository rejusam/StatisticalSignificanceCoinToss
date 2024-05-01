# The idea of statistical significance explained simply

Once upon a time, in a land where sports events were taken very seriously, there was a young statistician named Alex who was tasked with ensuring the fairness of a coin used in a prominent sporting event. The organizers had received a complaint suggesting that the coin might be biased, favoring one side over the other. Alex knew that this could potentially undermine the integrity of the event, and so she set out to investigate the matter scientifically. In a scientific approach to test the fairness of a coin, Alex followed these steps and explanations:

## Testing the Fairness of a Coin

### 1. Null Hypothesis and Alternative Hypothesis
- Null Hypothesis (H0): The coin is fair, meaning the probability of getting a head or a tail is 0.5 (50-50 chance).
- Alternative Hypothesis (H1): The coin is unfair, meaning the probability of getting a head or a tail is not equal to 0.5.

*Initial Coin Toss:* When we toss a coin and obtain heads, it raises the question: Does this result necessarily indicate a 50% chance?
*Second Coin Toss:* When we proceed to toss the coin a second time and again receive heads, if the chances are 50-50 is there a guarantee to get tail in the second toss? No, because it's important to note that each toss is an independent event. This means that the outcome of the first toss does not influence the outcome of the second toss. Therefore, even if the initial toss resulted in heads (or tails), the probability of getting heads or tails on subsequent tosses remains 50-50.

Now. the challenge lies in determining how many consecutive heads must be observed to infer that the coin is unfair, indicating a higher probability of landing heads. Obtaining heads in both tosses does not necessarily indicate that the coin is unfair. The crucial question is: How many consecutive heads must occur before we can reasonably conclude that the coin is biased?

### 2. Experimental Design
- Ask 100 people to toss the coin 10 times each and record the number of heads obtained.
- This provides a sample size of 1000 coin tosses for statistical analysis.

### 3. Data Collection and Distribution
- Collect the data (number of heads obtained in 10 tosses from each person).
- Plot the frequency distribution:
 - x-axis: Number of heads (ranging from 0 to 10)
 - y-axis: Frequency or count of people who obtained that number of heads

### 4. Expected Distribution under the Null Hypothesis
- If the coin is truly fair (H0 is true), the expected distribution of the number of heads should follow a binomial distribution with n = 10 (number of tosses) and p = 0.5 (probability of getting a head).
- Calculate or simulate the binomial distribution theoretically or using statistical software/programming languages.

### 5. Comparison of Observed and Expected Distributions
- Compare the observed frequency distribution (from the experiment) with the expected binomial distribution (under the null hypothesis of a fair coin).
- If the observed distribution deviates significantly from the expected distribution, it may provide evidence against the null hypothesis, suggesting that the coin is unfair.

### 6. Statistical Significance Testing
- Perform a statistical test, such as the chi-square goodness-of-fit test, to quantify the difference between the observed and expected distributions.
- Obtain the p-value, which represents the probability of obtaining the observed data (or more extreme data) if the null hypothesis is true.

### 7. Decision Criteria
- Set a significance level (e.g., $\alpha$ = 0.05 or 0.01) based on the desired level of confidence.
- If the p-value is less than the significance level ($\alpha$), reject the null hypothesis and conclude that the coin is unfair.
- If the p-value is greater than the significance level, fail to reject the null hypothesis, and there is no strong evidence to conclude that the coin is unfair.

By following this scientific approach, you can objectively evaluate the fairness of the coin based on empirical data and statistical analysis.

