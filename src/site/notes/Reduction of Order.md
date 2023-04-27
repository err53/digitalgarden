---
{"dg-publish":true,"permalink":"/reduction-of-order/"}
---

Given a solution to a second-order linear homogenous problem, can we find a second linearly independent of the homogenous problem and a solution to the non-homogenous problem

Given an equation in the form
$$
y''(x) + p(x) y'(x) + q(x) y(x) = g(x) \quad (*)
$$
1. Let $y_1(x)$ be a solution to the homogenous equation, and look at $y(x) = y_1(x) v(x)$:
   Thus, $$y'(x) = y_1(x) v'(x) + y_1'(x)v(x)$$ and $$y''(x) = y_1(x) v''(x) + 2y_1'(x)v'(x) + y_1''(x)v(x)$$
2. Substitute from 1 into $(*)$
3. Simplify
4. Let $w = v', w' = v''$. We get a first order linear ODE in $w$
5. Solve for $w$ using an integrating factor
6. Find $v(x)$
7. Substitute back into original $y(x) = y_1(x) v(x)$
   Solution will be in the form $$c_1 y_1(x) + c_2 y_2(x) + y_p(x)$$ where $y_2$ is the 2nd linearly independent solution of the homogenous problem and $y_p$ is a particular solution of $(*)$.