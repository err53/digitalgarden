---
{"dg-publish":true,"permalink":"/integrating-factor/"}
---

## Definition
If there is a function $\mu(x, y)$ such that

$$
\mu(x, y) M(x, y) dx + \mu(x, y) N(x, y) dy = 0
$$
is exact, then $\mu(x, y)$ is an integrating factor

## Finding Integrating factor

Let $\frac{\delta f}{\delta x} = f_x$ and $\frac{\delta f}{\delta y} = f_y$

- Solve $\mu_y M + \mu M_y = \mu_X N + \mu N_x$
	- PDE, so generally hard to solve, simplify by assuming $\mu(x, y) = \mu(x)$ or $\mu(x, y) = \mu(y)$
- If we assume $\mu(x, y) = \mu(x)$