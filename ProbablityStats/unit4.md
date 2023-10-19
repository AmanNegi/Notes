- **Binomial Distribution**:

  - The probability distribution of the binomial random variable X, representing the number of successes in n independent Bernoulli trials with probability of success p in each trial, is
  - `b(x; n, p) = nCx p^x (1-p)^n-x`, where `nCx = n!/(x!(n-x)!), x=0,1,...n`
  - The mean and variance are μ=np and σ²=np(1-p).

- **Negative Binomial Distribution**:

  - The probability distribution of the negative binomial random variable X, representing the number of trials required to obtain r successes in a sequence of independent Bernoulli trials with probability p of success in each trial, is
  - `nb(r,x; p) = x-1Cr-1 p^r (1-p)^x-r`, where x=r,r+1,...
  - The mean and variance are μ=r/p and σ²=r(1-p)/p²[^7^][7].

- **Geometric Distribution**:

  - The probability distribution of the geometric random variable X, representing the number of trials required to obtain the first success in a sequence of independent Bernoulli trials with probability p of success in each trial, is
  - `g(x; p) = p(1-p)^x-1`, where x=1,2,...
  - The mean and variance are μ=1/p and σ²=(1-p)/p²[^7^][7].

- **Poisson Distribution**:
  - The probability distribution of the Poisson random variable X, representing the number of outcomes occurring in a given time interval or specified region with mean λt, is
  - `p(x; λt) = e^(-λt)(λt)^x / x!`, where x=0,1,[^8^][8]...
  - The mean and variance are μ=λt and σ²=λt[^7^][7].
