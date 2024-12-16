---
tags:
  - "#math31-ap"
aliases:
  - 401. Basic Integration Rules
---
# 401. Basic Integration Rules

## 01. Integrals of Constants and Variables

Integration is the reverse operation for differentiation. 

For any constant, the integral is as follows. 

$$
\int c\ dx = cx + C
$$

When finding the integral of a variable raised to an exponent, the integral is as follows.

$$
\int x^n\, dx = \frac{x^{n+1}}{n + 1} + C
$$

If the variable has a constant being multiplied to it, simply perform the integration and simplify afterwards.

$$
\int cx^n\, dx = \frac{c \cdot x^{n+1}}{n + 1} + C
$$

The above two rules apply with variables which are in fractions ($\frac{1}{x^n}$) or roots ($\sqrt{x}$).

In the case of $x^{-1}$, it has a special property as performing the previous rules will result in a denominator of 0.

$$
\int \frac{1}{x} \ dx = \ln{x}
$$

This rule also applies with any constant being added to the denominator.

$$
\int \frac{1}{x + c} \ dx = \ln{x + c}
$$

## 02. Integrals of polynomials

For polynomials, simply split the integration between each term of the polynomial.

$$
\int ax^n \pm bx^k \pm c \ dx =
\int ax^n \, dx \pm \int bx^k \, dx  \pm \int c \ dx
$$
## 03. Functions

For functions which can be foiled, it is recommended to simply transform the function into a polynomial for integration.

If a numerator can be split into multiple terms and divide by the numerator, then performing the integration on the two separate terms is much easier.

$$
\int \frac{x^4 + 6x^3}{x} = \int x^3 + \int6x^2
$$

## 04. Separating Constants

When integrating, constant values can be left out of the integration. This is due to the property of linearity in integration.

$$
\int c \cdot f(x)\ dx = c \cdot \int{f(x) \ dx}
$$

## 05. Trigonometric Functions

Integration of trigonometric functions which contain a constant multiplied to $x$ is as follows.

$$
\int \cos{cx} = \frac{\sin{cx}}{c} + C
$$





