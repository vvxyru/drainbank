---
id: 502-volumes-perpendicular-to-given-axis
aliases:
  - 502. Volumes Perpendicular to Given Axis
tags:
  - math31ap
---

# 502. Volumes Perpendicular to Given Axis

## 01. Overview
---

Some questions require the volume to be found by a section bound by a graph.

Imagine a region bound by two graphs, in this example, $y=x^2$ and $y=\sqrt{x}$.

In this region, squares (or any shape) will emerge from the area between the two graphs at each point to form a 3D object. 

```functionplot
---
bounds: [0,2,0,2]
disableZoom: true
grid: true
---
f(x)=x^2
g(x)=sqrt(x)
```

These types of questions will come in a variety of forms. They may use different objects to build the 3D shape, or may also be in respect not the y-axis.

Depending on the question, it is important to utilize the distance between the two graphs to calculate the final volume of the shape.

For example, a question which requires squares in respect to the x-axis will use the vertical distance between the two graphs as a side length.

In a question which requires squares and is in respect to the y-axis, it will use the horizontal distance between the graphs.

It is important to know the formulas for each type of shape and how to determine the horizontal and vertical distance of each point between the bounded region.

## 02. Finding the Volume
---

As an example we will use the functions previously.

Before finding the volume, determine the region of the graphs which bound the shape. In the example above, the bounded region is between 0 and 1.

```functionplot
---
bounds: [0,1,0,1]
disableZoom: true
grid: true
---
f(x)=x^2
g(x)=sqrt(x)
```

We will determine the volume of cross sections perpendicular to the x-axis being squares.

First, we determine the equation which will give us the formula and the function which provides the area of one shape.

For this, we will use the general equations of:

$$
\begin{aligned}
&\text{1. Cross sections of area A(x) taken perpendicular to the x-axis.} \\
&\text{Volume} = \int_{a}^{b} A(x)dx \\
&\text{2. Cross sections of area A(y) taken perpendicular to the y-axis.} \\
&\text{Volume} = \int_{c}^{d} A(y)dy \\
\end{aligned}
$$

In the example above, the formulas will be:

$$
\begin{aligned}
V &= \int_{a}^{} f(x)dx\\
\end{aligned}
$$





