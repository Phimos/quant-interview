---
description: Probability
---

# Obtuse Triangle in a Circle

### Description

Suppose we randomly pick 2 points A, B _**within**_ a circle centered at point O. What is the probability that the triangle formed by ABO is an obtuse one?

### Solution

Assume WLOG that A is at least as far away as B. And let $$|OA|=r$$.

"Rotated" the point A to be directly above O, B is somewhere in (or on) the concentric circle passing through A, with a uniform distribution.

Obtuse triangle contains one obtuse angle:

* First case, $$\angle AOB \ge 90^\circ$$, corresponds to B in the lower half of A-circle.
* Second case, $$\angle ABO \ge 90^\circ$$, means B is in a smaller circle, half as tall as the A-circle and fitting neatly in its upper half.
* Third case, $$\angle OAB \ge 90^\circ$$, **is impossible**.

Adding the probabilities corresponding to the first and second cases, we can obtain the final probability of $$\frac12+\frac14=\frac34$$.
