# Broken Bar

### Description

A chocolate bar fell to the ground and randomly broke in $$n$$ pieces. What is the expected size of the smallest piece? What is the expect size of the $$k$$-th largest piece?

### Solution

Consider random variables $$X_1, \ldots,X_{n-1}, i.i.d \sim \mathcal{U}(0, 1)$$. Putting them in ascending order generates $$X_{(1)},\ldots,X_{(n-1)}$$. By symmetry, the joint probability density function of $$X_{(1)},\ldots,X_{(n-1)}$$ would be:

$$
f_{X_{(1)},\ldots,X_{(n-1)}}(x_1,\ldots,x_{n-1})=(n-1)!
$$

