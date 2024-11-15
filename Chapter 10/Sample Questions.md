## Chapter 10.1 - 10.2
### Exercise 10.2: 
An experimenter has prepared a drug dosage level that she claims will induce sleep for $80\%$ of people suffering from insomnia. After examining the dosage, we feel that her claims regarding the effectiveness of the dosage are inflated. In an attempt to disprove her claim, we administer her prescribed dosage to $20$ insomniacs and we observe $Y$, the number for whom the drug dose induces sleep. We wish to test the hypothesis $H\_{0}: p = .8$ versus the alternative, $H_{a}: p < .8$. Assume that the rejection region $\{y \leq 12 \}$ is used.
* Experiment follows $Y \sim Binom(n=20, p= .8)$
* Type I Error: $\alpha = P(  Y \leq 12 \vert p=0.8)$ In Reject Region but $H_{0}$ is true
* Type II Error: $\beta = P( Y > 12 \vert p=0.6)$
> Assume that $p = 0.6 , 0.4$:


### Example 10.6:
A machine in a factory must be repaired if it produces more than $10\%$ defectives among the large lot of items that it produces in a day. A random sample of 100 items from the day’s production contains 15 defectives, and the supervisor says that the machine must be repaired. Does the sample evidence support his decision? Use a test with level .01.
* Let $p$ denote the proporition of defectives
* $H_{0}: = .1$ Defectives
* $H_{1}: > .1$
* $$Z = \frac{\hat{p}- p_{0}}{\sigma_{\hat{p}}} = \frac{.15 - .1}{\sqrt{\frac{(0.1)(1-0.1)}{100}}} = \frac{5}{3} = 1.667$$
* $P(Z > 1.667) = 0.0475$
* $P(Z > 2.33) = 0.01$

Alternative

* $$1 - \sum\limits_{y=0}^{?}  \binom{100}{y} p^{y} (1-p)^{n-y} = 0.99$$

$\therefore$ at the $\alpha = 0.01$ level of significance, there is NOT sufficient evidence to support the statement that the machine must be repaired

## Chapter 10.3 - 10.4

### Exercise 10.21
Shear strength measurements derived from unconfined compression tests for two types of soils gave the results shown in the following table (measurements in tons per square foot). Do the soils appear to differ with respect to average shear strength, at the 1% significance level?

|Soil Type I| Soil Type II|
|-----------|-----------|
|$n_{1} = 30$|

$H_{0}: \mu_{1} - \mu_{2} = 0$

### Exercise 10.33

A political researcher believes that the fraction $p_{1}$ of Republicans strongly in favor of the death 
penalty is greater than the fraction $p_{2}$ of Democrats strongly in favor of the death penalty. He
acquired independent random samples of $200$ Republicans and $200$ Democrats and found $46$
Republicans and $34$ Democrats strongly favoring the death penalty. Does this evidence provide
statistical support for the researcher's belief? Use $\alpha = .05$.

$H_{0}: p_{1} - p_{2} = 0$

$H_{1}: p_{1} - p_{2} > 0$

$$
\begin{align*}
TS = &\frac{\hat{p}_{1} - \hat{p}_{2} - 0}{SE(\hat{p}_{1} - \hat{p}_{2})} \\
=& \frac{\hat{p}_{1} - \hat{p}_{2} - 0}{\hat{p} (1- \hat{p}) (\frac{1}{200} + \frac{1}{200})}\\
= &\frac{\frac{46}{200} + \frac{34}{200}}{0.2 (1-0.2) (\frac{1}{200} + \frac{1}{2000})} 
&= 1.5
\end{align*}
$$

$RR = \{ TS > z_{0.05} = 1.644854 \}$

Decision: Because $1.64 > 1.5$, we cannot reject $H_{0}$

$\therefore$ At the significance level, $\alpha = 0.05$ there is not sufficient evidence two support
Republicans strongly favor death penalty compared to Democrats

> Note: In these circumstance we can assume ${p}_{1} = p_{2}$

> $\hat{p} = \frac{y_{1} + y_{2}}{200 + 200} $


### Exercise 10.20
The Rockwell hardness index for steel is determined by pressing a diamond point into the
steel and measuring the depth of penetration. For 50 specimens of an alloy of steel, the Rock-
well hardness index averaged 62 with standard deviation 8. The manufacturer claims that this
alloy has an average hardness index of at least 64. Is there sufficient evidence to **refute** the
manufacturer’s claim at the 1% significance level?

$H_{0}:$ Average hardness index is $64 \Leftrightarrow  \mu = 64$

$H_{1}:$ Average hardnesss index is $< 64$

$$
TS = \frac{\bar{Y} - \mu_{0}}{SE(\bar{Y})} 
$$

$$ts = \frac{62-64}{} = -1.767
$$

> Although question ask **at least**, we are tying to **refute**, so we need $<$



## Example 10.30
$\theta = p$

$H_{0}$: 20% of public preferred her product

$H_{1}$: <20% ''

$$TS = \frac{\hat{p} - 0.2}{\frac{p_{0} (1-p_{0})}{n}}=\frac{\hat{p} - 0.2}{\frac{0.2(0.8)}{n}}$$
$$RR \{ TS  \leq z_{0.05} \} \Rightarrow \frac{\hat{p} - 0.2}{\frac{0.2(0.8)}{n}} < 1.64 \Rightarrow \hat{p} < 0.13$$
