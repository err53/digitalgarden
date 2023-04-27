---
{"dg-publish":true,"permalink":"/integrating-factor-for-second-order-od-es/"}
---

## Definition
If there is a function $\mu(x, y)$ such that

$$
\mu(x, y) M(x, y) dx + \mu(x, y) N(x, y) dy = 0
$$
is exact, then $\mu(x, y)$ is an integrating factor

## Finding Integrating factor

Let $\frac{\partial f}{\partial x} = f_x$ and $\frac{\partial f}{\partial y} = f_y$

- Solve $\mu_y M + \mu M_y = \mu_x N + \mu N_x$
	- PDE, so generally hard to solve, simplify by assuming $\mu(x, y) = \mu(x)$ or $\mu(x, y) = \mu(y)$
- If we assume $\mu(x, y) = \mu(x)$, equation reduces to
$$
\mu M_y = \mu_x N + \mu N_x \Longrightarrow \frac{d \mu}{dx} = \mu(x) \frac{M_y - N_x}{N}
$$
- Assume, $\mu(x, y) = \mu(y)$, reduces to
$$
\mu_y M + \mu M_y = \mu N_x \Longrightarrow \frac{d \mu}{dy} = \mu(y) \frac{N_x - M_y}{M}
$$

