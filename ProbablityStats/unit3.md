
- **Mean of a Random Variable**: 
    - The mean or expected value of a random variable X, denoted by E(X) or μ, is the long-run average value of X. 
    - It is defined as `E(X) = ∑x x*f(x)` for discrete X, and `E(X) = ∫x x*f(x) dx` for continuous X.

- **Variance and Standard Deviation**: 
    - The variance of a random variable X, denoted by Var(X) or σ², measures the spread or variability of X. 
    - It is defined as `Var(X) = E[(X - μ)²] = E(X²) - [E(X)]²`. 
    - The standard deviation of X, denoted by SD(X) or σ, is the square root of the variance.

- **Covariance and Correlation**: 
    - The covariance of two random variables X and Y, denoted by Cov(X, Y), measures the linear relationship between them. 
    - It is defined as `Cov(X, Y) = E[(X - μx)(Y - μy)] = E(XY) - E(X)E(Y)`.
    - The correlation coefficient of X and Y, denoted by ρ or Corr(X, Y), is the normalized measure of their linear relationship. 
    - It is defined as `ρ = Cov(X, Y)/(SD(X)SD(Y))`, where `-1 ≤ ρ ≤ 1`.

- **Linear Combination of Random Variables**: 
    - A linear combination of random variables is a random variable of the form `Z = aX + bY + c`, where a, b, and c are constants. 
    - The mean of Z is given by `E(Z) = aE(X) + bE(Y) + c`.
    - The variance of Z is given by `Var(Z) = a²Var(X) + b²Var(Y) + 2abCov(X, Y)`.

- **Chebyshev's Theorem**: 
    - Chebyshev's theorem states that for any random variable X and any positive number k, the probability that X deviates from its mean by more than k standard deviations is at most 1/k². That is, `P(|X - μ| ≥ kσ) ≤ 1/k²`.
