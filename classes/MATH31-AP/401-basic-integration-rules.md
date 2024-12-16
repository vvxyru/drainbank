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
\int c\ \text{dx} = cx + C
$$

$$
\int \pi \text{dy} = \pi y + C
$$


When finding the integral of a variable raised to an exponent, the integral is as follows.
$$
\int x^n\, \text{dx} = \frac{x^{n+1}}{n + 1} + C
$$

If the variable has a constant being multiplied to it, simply perform the integration and simplify afterwards.
$$
\int cx^n\, \text{dx} = \frac{c \cdot x^{n+1}}{n + 1} + C
$$
The above two rules apply with variables which are in fractions ($\frac{1}{x^n}$) or 
## 02. Integrals of polynomials

For polynomials, simply split the integration between each term of the polynomial.

$$
\int ax^n \pm bx^k \pm c \ \text{dx} =
\int ax^n \, \text{dx} \pm \int bx^k \, \text{dx}  \pm \int c \ \text{dx}
$$
## 03. Functions

For functions which can be foiled, it is recommended to simply transform the function into a polynomial for integration.

If a numerator can be split into multiple terms and divide by the numerator, then performing the integration on the two separate terms is much easier.

$$
\int \frac{x^4 + 6x^3}{x} = \int x^3 + \int6x^2
$$






