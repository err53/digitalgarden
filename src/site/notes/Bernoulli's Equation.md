---
{"dg-publish":true,"permalink":"/bernoulli-s-equation/"}
---

$$
y' + P(x)y = Q(x)y^n
$$

## Solving
1. Change variables: $v(x) = y^{1-n}, \frac{dv}{dx} = (1-n)y^{-n} \frac{dy}{dx}$
2. Differentiate both sides wrt $x$ where $y = y(x)$, and simplify $$\frac{1}{1-n}\frac{dv}{dx} = \frac{1}{y^n}\frac{dy}{dx}$$
3. Divide both sides of the original ODE by $y^n$, simplify $$\frac{1}{y^n}\frac{dy}{dx} + P(x) y^{1-n} = Q(x)$$
4. Substitute with change to $v$ variable to obtain first order ODE
5. Solve ODE for $v(x)$
6. Substitute $v = y^{1-n}$ to return to original variables $y(x)$