1 Find the likelihood for a random sample $y_1, ..., y_n$ from the geometric density $Pr(Y = y) = \pi(1 - \pi)^y$, $y = 0, 1, ...$, where $0<\pi<1$.

2 (a) Show that the log likelihood for a random sample from density $f(y; \lambda, \kappa) = \frac{\lambda^\kappa y^{\kappa-1}}{\Gamma(\kappa)}\exp(-\lambda y)$ is 

  $$\iota(\lambda, \kappa) = n\kappa \log\lambda + (\kappa - 1)\sum{\log y_j} - \lambda\sum{y_j} - n\log\Gamma(\kappa)$$.

  deduce that the observed information is 

  $$J(\lambda, \kappa) = n \begin{bmatrix}{{\kappa/\lambda^2}}&{{-1/\lambda}}\\{{-1/\lambda}}&{{d^2 \log\Gamma(\kappa)/d\kappa^2}}\end{bmatrix}$$,

   and find the expected information $I(\lambda, \kappa)$.

   (b) Suppose that we write $\lambda = \kappa / \mu$, where $\mu$ is the distribution mean. Find the log likelihood in terms of $\mu$ and $\kappa$, and show that $I(\mu, \kappa) = n \begin{bmatrix}2\kappa/\mu^2 & 0\\0 &d^2\log\Gamma(\kappa)/d\kappa^2-1/\kappa\end{bmatrix}  $ .

3 Find the expected information for $\theta$ based on a random sample *Y~1~*, ..., *Y~n~* from the geometric density

$$f(y;\theta) = \theta(1 - \theta)^{y-1}$$, $y = 1, 2, 3, ...$, $0<\theta<1$.

A statistician has a choice between observing random samples from the Bernoulli or geometric densities with the same $\theta$. Which will give the more precise inference on $\theta$?

4 If the log likelihood for a $p\times 1$ vector of parameters is $\iota(\theta) = a + b^\mathrm T\theta - \frac{1}{2}\theta^\mathrm TC\theta$, where the constants $a$, $b$ and $C$ are respectively scalar, a $p \times 1$ vector, and a $p\times p$ symmetric positive definite matrix, show that the score statistic can be written $b - C\theta$. Find the observed information $J(\theta)$, and show that $\hat{\theta}$ is attained in one step from any initial value of $\theta$.

 $\hat{\theta} \dot{=} \theta^\dagger + J(\theta^\dagger)^{-1}U(\theta^\dagger)$

5 If $Y_1, ..., Y_n$ is a random sample from density $\theta^{-1}e^{-x/\theta}$, show that the maximum likelihood estimator $\hat{\theta}$ has an asymptotic normal distribution with mean $\theta$ and variance $\theta^2/n$. 

6 If $Y_1, ..., Y_n$ is a random sample from the $N(\mu, \sigma^2)$ distribution with known $\sigma^2$, show that the likelihood ratio statistic for comparing $\mu = \mu^0$ with general $\mu$ is $W(\mu^0) = n(\bar{Y}-\mu)^2/\sigma^2$. Give the likelihood ratio confidence region for $\mu$.