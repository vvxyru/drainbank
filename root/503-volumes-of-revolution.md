---
id: 503-volumes-of-revolution
aliases:
  - 503. Volumes of Revolution
tags:
  - math31ap
---

# 503. Volumes of Revolution

## 01. Overview
---

When rotating a graph around each axis, we can create three-dimensional objects which we can calculate the volume for. 

The process is similar to the process of finding the area between curves ([[501-area-between-curves]]), but with slight modifications. 

## 02. Disk Method 

For a continuous graph which revolves around the x-axis, we can imagine an infinite number of disks spanning throughout the object.

```functionplot
---
bounds: [0,2,-4,4]
disableZoom: true
grid: true
---
f(x)=x^2 
f(x)=-x^2
```

Each disk will be at every $x$ value in the boundaries of the object. In this example, we will look at the volume at $0 \leq x \leq 1$.

To find the volume, we will be using familiar equations, being the integral of the graph and the formula for the area of each segmented disk.

$$
V = \int_{0}^{1} A(x)dx

$$









