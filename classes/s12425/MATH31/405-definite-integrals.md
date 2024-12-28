---
tags:
  - "#math31-ap"
aliases:
  - 405. Definite Integrals
---
# 405. Definite Integrals

Definite integrals use an upper and lower bound to describe the area which the integral is defined in. 

It represents the area between the curve and the $x$-axis, which can be positive or negative.

Knowing this, in some cases we can end up with negative area, which doesn't reflect the total area under a curve if negative. 
- In this case, we would use the integral of the same boundaries with the absolute value of the function in order to have an accurate depiction of the area. 

In general, 

$$
\int_a^b f(g(x))\,g'(x)\,dx = \int_{g(a)}^{g(b)}f(u)\,du
$$

This example is used in [integration by substitution](402-integration-by-substitution.md)