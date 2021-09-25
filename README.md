# Data-Science-Reading-Assignments

## Reading Assignment #1

<details>

  <summary>Section 4.2.1 (Bernoulli Distribution)</summary>
  </blockquote>
* What is a Bernoulli random variable?

  <blockquote>

  A Bernoulli random variable is a random variable where each individual trial only has two possible outcomes, often labeled as a *success* or *failure*.

  </blockquote>

* What is the connection between the binomial distribution and a Bernoulli random variable? [Refer to section 4.3.1 if it has been a while since you looked at the binomial distribution.]

  <blockquote>

A Bernoulli random variable is a requirement for a binomial distribution. In particular, a binomial distribution is the distribution of _r_ successes in _n_ trials of a Bernoulli variable.

  </blockquote>


* What is the largest possible standard deviation for a Bernoulli random variable?

  <blockquote>

  The largest possible standard deviation for a Bernoulli random variable would occur when _p_ and _(1-p)_ are equal, i.e., when _p = 0.5_. Thus, we want the square root of (0.5)<sup>2</sup>, giving us 0.5 as the maximum possible standard deviation for a Bernoulli random variable.

  </blockquote>


</details>

<details>

  <summary>Sections 9.5.1 - 9.5.3 (Logistic Regression)</summary>

* For what type of response/target variables is logistic regression appropriate?

  <blockquote>

  Logistic regression is appropriate "for response variables where regular multiple regression does not work very well...where the residuals look completely different from the normal distribution," (371). More specifically, the target variable is a two-level categorical variable, Y<sub>i</sub> whose outcome can take the values 1 or 0 with respective probabilities p<sub>i</sub> and 1-p<sub>i</sub>.

  </blockquote>

* Look at the logistic model in Example 9.31. How can we interpret the coefficient of 0.8668 on the honors variable?

  </blockquote>

The coefficient 0.8668 on the honors variable indicates that the logit transformation of p<sub>i</sub>, the probability of a callback, is expected to increase by 0.8668 when honors are present on a resume.

  </blockquote>

* When using the Akaike information criterion for model selection, which is better, a large AIC or a small AIC?

  <blockquote>

A small AIC is better: "We look for models with a lower AIC through a backward elimination strategy," (374)

  </blockquote>

* How are linear and logistic regression similar? How are they different?

  <blockquote>

  Linear and logistic regression are similar in that both assume that the target variable is linearly related--or related to linearly related--to a series of predictor variables (when all others are held constant). Put more coarsely, the righthand side of the equation looks roughly the same for both linear and logistic regression, with a series of predictor variables attached to linear coefficients. However, the lefthand side of these equations is different, thus comprising the difference in the types of regression. The target variable of linear regression is numerical, often continuous, and could assume a wide range of values. No transformation is performed on this variable, so its relationship to the predictor variables is *actually* linear. In logistic regression, the target variable is binary, and its probability is logarithmically transformed before the linear relationship is used.

  </blockquote>

</details>
