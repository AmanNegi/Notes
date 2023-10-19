- **Probability Function of a Discrete Random Variable**: 
    - `f(x) = P(X = x)`
    - Conditions: `f(x) ≥ 0` for all x, and the sum of `f(x)` over all possible values of x is 1.

- **Probability Density Function of a Continuous Random Variable**: 
    - `f(x)`
    - Conditions: `f(x) ≥ 0` for all x, and the integral of `f(x)` over the entire range of x is 1. 
    - The probability that X lies in an interval (a, b) is given by the integral of `f(x)` from a to b.

- **Cumulative Distribution Function**: 
    - `F(x) = P(X ≤ x)`
    - Conditions: `F(x)` is nondecreasing, `F(x)` approaches 0 as x approaches -∞, and `F(x)` approaches 1 as x approaches ∞. 
    - The relation between `F(x)` and `f(x)` is `F(x) = ∫x -∞ f(t) dt` for continuous X, and `F(x) = ∑x t=-∞ f(t)` for discrete X.

- **Joint Probability Function of Two Discrete Random Variables**: 
    - `f(x, y) = P(X = x and Y = y)`
    - Conditions: `f(x, y) ≥ 0` for all (x, y), and the sum of `f(x, y)` over all possible values of (x, y) is 1.

- **Joint Probability Density Function of Two Continuous Random Variables**: 
    - `f(x, y)`
    - Conditions: `f(x, y) ≥ 0` for all (x, y), and the integral of `f(x, y)` over the entire plane is 1. 
    - The probability that (X, Y) lies in a region R is given by the double integral of `f(x, y)` over R.

- **Marginal Probability Function or Density Function**: 
    - For X: `g(x) = ∑y f(x, y)` or `g(x) = ∫y f(x, y) dy`
    - For Y: `h(y) = ∑x f(x, y)` or `h(y) = ∫x f(x, y) dx`

- **Conditional Probability Function or Density Function**: 
    - For X given Y = y: `f(x|y) = f(x, y)/h(y)`
    - For Y given X = x: `f(y|x) = f(x, y)/g(x)`

- **Statistical Independence**: 
    - Two random variables X and Y are said to be statistically independent if and only if their joint probability function or density function can be written as the product of their marginal probability functions or density functions. That is, `f(x, y) = g(x)h(y)`.
