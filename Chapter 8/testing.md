# Unbiased Point Estimators

## Unbiased Point Estimators $\hat{\theta}$

| Target Parameter $\theta$ | Sample Size(s) | Point Estimator $\hat{\theta}$ | $E(\hat{\theta})$ |  $Var(\hat{\theta})$ | Standard Error $\sigma_{\hat{\theta}}$ |
| :--- |  :--- | :--- | :--- | :--- | :--- |
| $\mu$ | $n$ |  $\bar{Y} = \frac{1}{n} \sum\limits_{i=1}^{n} Y_{i}$ | $\mu$ |  $\frac{\sigma^{2}}{n}$ | $\frac{\sigma}{\sqrt{n}}$ |
| $p$ | $n$ |  $\hat{p} = \frac{1}{n} \sum\limits_{i=1}^{n} Y_{i}$ | $p$ |  $\frac{pq}{n}$ | $\sqrt{\frac{pq}{n}}$ |
| $\mu_{1} - \mu_{2}$ | $n_{1} \hspace{1mm} n_{2}$ | $$ \bar{Y} _1 - \bar{Y} _2 $$ $$= \frac{1}{n_{1}} \sum\limits_{i=1}^{n_{1}} Y_{i}^{(1)} - \frac{1}{n_{2}} \sum\limits_{i=1}^{n_{2}} Y_{i}^{(2)} $$  | $\mu_{1} - \mu_{2}$ | $$\frac{\sigma^{2}_{1}}{n_{1}} + \frac{\sigma_{2}^{2}}{n_{2}} $$ | $$\sqrt{ \frac{ \sigma^{2}_{1} } { n_{1} } + \frac{ \sigma_{2}^{2}}{ n_{2} } } $$ |
| $p_{1} - p_{2} $ | $n_{1} \hspace{1mm} n_{2}$ |  $\hat{p_{1}} - \hat{p_{2}} = \frac{1}{n_{1}} \sum\limits_{i=1}^{n_{1}} Y_{i}^{(1)} - \frac{1}{n_{2}} \sum\limits_{i=1}^{n_{2}} Y_{i}^{(2)}$ | $p_{1} - p_{2}$ |  $\frac{p_{1}q_{1}}{n_{1}} + \frac{p_{2}q_{2}}{n_{2}}$ | $\sqrt{\frac{p_{1}q_{1}}{n_{1}} + \frac{p_{2}q_{2}}{n_{2}}}$ |


Experiments
$$ \bar{Y}\_{1} - \bar{Y}\_{2} $$

$$= \frac{1}{n\_{1}} \sum\limits_{i=1}^{n\_{1}} Y\_{i}^{(1)} - \frac{1}{n\_{2}} \sum\limits_{i=1}^{n\_{2}} Y\_{i}^{(2)} $$ 

$$ \bar{Y} _1 - \bar{Y} _2 $$

$$= \frac{1}{n_{1}} \sum\limits_{i=1}^{n_{1}} Y_{i}^{(1)} - \frac{1}{n_{2}} \sum\limits_{i=1}^{n_{2}} Y_{i}^{(2)} $$ 

New

$$ \bar{Y} _1 - \bar{Y} _2 = \frac{1}{n\_{1}} \sum\limits_{i=1}^{n\_{1}} Y\_{i}^{(1)} - \frac{1}{n\_{2}} \sum\limits_{i=1}^{n\_{2}} Y\_{i}^{(2)} $$ 