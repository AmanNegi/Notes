- **Uniform Distribution**:
    - The probability density function of the uniform random variable X, representing the outcome of a random experiment that has equally likely outcomes over an interval (a, b), is
    - `f(x) = 1/(b-a)`, for `a < x < b`
    - The mean and variance are μ=(a+b)/2 and σ²=(b-a)²/12.

- **Normal Distribution**:
    - The probability density function of the normal random variable X, representing the outcome of a random experiment that has a bell-shaped distribution with mean μ and variance σ², is
    - `f(x) = 1/(√(2π)σ) e^(-(x-μ)²/(2σ²))`, for `-∞ < x < ∞`
    - The standard normal distribution is a special case when μ=0 and σ²=1.

- **Exponential Distribution**:
    - The probability density function of the exponential random variable X, representing the time until the occurrence of a Poisson event with mean rate β, is
    - `f(x) = βe^(-βx)`, for `x > 0`[^1^][1]
    - The mean and variance are μ=1/β and σ²=1/β².

- **Gamma Distribution**:
    - The probability density function of the gamma random variable X, representing the time until the occurrence of α Poisson events with mean rate β, is
    - `f(x) = β^α x^(α-1) e^(-βx) / Γ(α)`, for `x > 0`[^1^][1]
    - The mean and variance are μ=α/β and σ²=α/β².

- **Beta Distribution**:
    - The probability density function of the beta random variable X, representing a proportion or a fraction that varies between 0 and 1 with parameters α and β, is
    - `f(x) = x^(α-1) (1-x)^(β-1) / B(α, β)`, for `0 < x < 1`[^1^][1]
    - The mean and variance are μ=α/(α+β) and σ²=αβ/((α+β)²(α+β+1)).

- **Lognormal Distribution**:
    - The probability density function of the lognormal random variable X, representing a positive variable whose logarithm follows a normal distribution with mean μ and variance σ², is
    - `f(x) = 1/(√(2π)σx) e^(-(ln(x)-μ)²/(2σ²))`, for `x > 0`
    - The mean and variance are μ=e^(μ+σ²/2) and σ²=(e^(σ²)-1)e^(2μ+σ²).
