# 7.1 Hypothesis testing
- [[Null Hypothesis]]
- [[Alternate Hypothesis]]
- [[Hypothesis Test]]
- [[Test Statistic]]
- [[One-tailed test]]
- [[Two-tailed test]]
- [[Critical region]]
- [[Critical value]]
- [[Significance level]]
## Example 1
Suppose in a random sample of 10 games, Sarah had won 5 times. Is this enough to reject [[Null Hypothesis]] and say that she is cheating
Let X represent the number of times that Sarah wins in a sample of 10 games, if the null hypothesis is true
$X \sim B(10,\frac{1}{4})$
$P(X\geq5) = 1-P(X\leq4) = 1-0.9219 = 0.0781 \: (7.81\%)$
The probability is larger than 5% (usual [[Significance level]]) and so we have no reason to reject $H_0$ 
## Test procedure summary
1. Identify the population parameter $\theta$ that you are going to test
2. Write down $H_0$ and $H_1$
	- [[Alternate Hypothesis]] will determine weather it's a [[One-tailed test]] or a [[Two-tailed test]]
3. Specify the [[Significance level]]
4. Find out weather observed value of [[Test Statistic]] falls in the [[Critical region]]
5. State your conclusion by addressing points
	- Is the result significant or not
	- What are the implications in terms of the context of original problem
# 7.2 Critical Values
- [[Actual Significance]]
# 7.3 [[One-tailed test]]
To carry out a [[One-tailed test]] you need to:
- Formulate a model for the [[Test Statistic]]
- Identify a suitable [[Null Hypothesis]] and [[Alternate Hypothesis]]
- Calculate the probability of the [[Test Statistic]] talking the observed value (or higher/lower) assuming the [[Null Hypothesis]] is true
- Compare this to the significance level
- Write a conclusion in the context of the question
# 7.4 [[Two-tailed test]]
To carry out a [[Two-tailed test]] you need to:
- Formulate a model for the [[Test Statistic]]
- Identify a suitable [[Null Hypothesis]] and [[Alternate Hypothesis]]
- Calculate the probability of the [[Test Statistic]] talking the observed value (or higher/lower) assuming the [[Null Hypothesis]] is true
- Compare this to half the significance level
- Write a conclusion in the context of the question