# Chapter 8 Questions + Solutions

### Question 8.3
Suppose that $\hat{\theta}$ is an estimator of $\theta$ and $E[\hat{\theta}] = a \theta + b$ for some nonzero constants $a$ and $b$.

What is $Bias[\hat{\theta}],$ in terms of $a, b, \theta$?

* $Bias[\hat{\theta}] = E[\hat{\theta}] - \theta = a \theta + b - \theta$

Find a function of $\hat{\theta}$ that is an unbiased estimator for $\theta$.



### Question 8.9

Suppose that $Y_{1}, Y_{2}, ..., Y_{n}$ consitute a random sample from a population with probability density function 

$$f(y) = \begin{cases}
\begin{align*}
&\frac{1}{\theta + 1} e^{\frac{-y}{\theta + 1}}, & \quad y > 0, \theta > -1  \\
&0, & \quad \text{elsewhere}.
\end{align*}
\end{cases}
$$
Suggest a suitable statistic to use as an unbiased estimator for $\theta$

Recall: Exponenital Distribution $f(y) = \frac{1}{\beta}e^{\frac{-y}{\beta}}$

Since $E[Y]= \beta = 1 + \theta$ We want $ E[\hat{\theta}] = \theta \rightarrow \hat{\theta} -1$. 

### Question 8.12

The reading on a volatage meter connected to a test circut is unfiromly distributed over the inverval $(\theta, \theta + 1),$ where $\theta$ is the true but unknown voltage of the circut. Suppose that $Y_{1}, Y_{2}, ..., Y_{n}$ denote a random varaible of such reading.

Show that $\overline{Y}$ is biased for estimating $\theta$
* 

Find an unbiased estimator 

Find $MSE(\overline{Y})$

### Question 8.14
Let $Y_{1}, Y_{2}, ..., Y_{n}$ denote a random sample of size $n$ from a population