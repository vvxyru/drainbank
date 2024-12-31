---
id: 501-area-between-curves
aliases:
  - 501. Areas between Curves
tags:
  - math31ap
---

# 501. Areas between Curves

## 01. Overview
---
When finding the area between two curves, $f(x)$ and $g(x)$,
We can subtract the upper graphs area under the curve from the lower graphs.

In this example, we subtract the integrals $x^2$ from $x$.
```functionplot
---
title: 
xLabel: x
yLabel: y
bounds: [0,2,0,2]
disableZoom: true
grid: 
---
f(x) = x^2
g(x) = x
```
## 02. Formula
---

In general, for an area between two curves bound by $f(x)$ and $g(x)$, and in the domain of $a$ and $b$, we can use this formula:

$$
\text{Area} = \int_a^b f(x) - \int_a^b g(x) dx
$$

$a$ will be the lower bound for the area, whereas $b$ will be the upper bound.

In the example above, the bounds of the area will be where the curves intersect, or when:

$$
\begin{align}
f(x) &= g(x)
\\ 
x^2 &= x
\\
\therefore x &= 0, 1
\end{align}
$$

When a question gives the functions with respect to $y$, it is the same process but the area is in respect to the y-axis. In solving, simply integrate with respect to $y$.











