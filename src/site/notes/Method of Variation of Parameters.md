---
{"dg-publish":true,"permalink":"/method-of-variation-of-parameters/"}
---

Consider the 2nd order linear ODE in standard form:

$$
y''(x) + p(x) y'(x) + q(x) y(x) = g(x)
$$

where $p(x)$, $q(x)$ and $g(x)$, are continuous on the interval of interest

1. Put ODE in standard form
2. Look for a particular solution of the form $y_p(x) = u_1(x) y_1(x) + u_2(x) y_2(x)$
   with $y_1, y_2$ as linearly independent solutions to the homogenous problem
3. $$u_1' = \frac{-y_2 g(x)}{W(y_1, y_2)}, u_2' = \frac{y_1 g(x)}{W(y_1, y_2)}$$
4. $$u_1(x) = \int u_1'(x) dx \textrm{ and } u_2(x) = \int u_2'(x) dx$$
5. $$
   y(x) = y_{gen}(x) = 
   \underbrace{c_1 y_1(x) + c_2 y_2(x)}_{y_c(x)} + 
   \underbrace{u_1(x) y_1(x) + u_2(x) y_2(x)}_{y_p(x)}
   $$
