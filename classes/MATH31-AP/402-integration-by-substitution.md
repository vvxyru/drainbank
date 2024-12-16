---
tags:
  - math31-ap
aliases:
  - 402. Integration by Substitution
---
# 402. Integration by Substitution

## 01. u-substitution

This method of integration is, in essence,  the reverse engineering of the chain rule. 

It simplifies the function in which is being integrated, allowing the use of simple integration rules when solving a problem.

$$
\int x^2 \sin{x^3} \ dx
$$

In this example, we are taking a look at this complex function. 

First step is to replace a nested complicated expression with the variable of $u$. In this case, $x^3$ seems to match this description.

After this, we must change the integration to respect our substituted variable of $u$, so we must change $dx$ to $du$.

$$
\begin{align}
u &= x^3 \\
du &= 3x^2 \\
\frac{du}{3x^2} &= dx
\end{align}
$$

With this, simply substituting in the respective values of $x^3$ and $dx$ will simplify the integral.

$$
\int \sin{u} \ \frac{du}{3}
$$

After, we simply use the [integration principle of linearity ](401-basic-integration-rules)to remove the denominator of $du$, leaving us with a simple trigonometric integration rule.

$$
\frac{1}{3} \int \sin{u} \ du = -\frac{1}{3}\cos{u} + C
$$

Finally, substituting $u$ with $x^3$ stated earlier gives us the final integral.

$$
\int x^2 \sin{x^3} \ dx = -\frac{1}{3}\cos{x^3} + C
$$

## 02. Integration by Parts

This method of integration is based on the product rule for differentiation but reversed, making it useful for solving integrals of products of functions.

To perform this method of integration, we use the following formula.

$$
\int u \, dv = uv - \int v \, du
$$

In this example, we are looking at this integral.

$$
\int x \cdot \cos{x}
$$

First, we are selecting the variable of $u$ as well as $dv$ from the original integral.
- $u$ as the part of the function that simplifies when differentiated.
- $dv$ as the part of the function that is straightforward to integrate.

$$
u = x, \quad dv = \cos{x} \, dx
$$

Now calculate the selected substitutions.
$$
du = dx, \quad v = \int \cos{x} \, dx = \sin{x}
$$

After this, we apply the substituted values back into the formula.

$$
\int x \cos{x} \, dx = x \sin{x} - \int \sin{x} \, dx
$$

Then, we calculate the integrals of the substituted values in the formula.

$$
\int x \cos{x} \, dx = x \sin{x} - (-\cos{x})
$$

Now, all there is left to do is to simplify the equation.
$$
\int x \cos{x} \, dx = x \sin{x} + \cos{x} + C
$$