---
{"dg-publish":true,"permalink":"/existence-and-uniqueness-theorem-for-first-order-nonlinear-differential-equations/"}
---

# Existence
If $f$ is continuous on an open rectangle
$$R = \{(x, y) \in \mathbb{R^2} : a < x < b, c < y < d\}$$
in the $x, y$ plane, and let $(x_0, y_0) \in \mathcal{R}$ be a fixed point in the rectangle.
Then, the IVP
$$
\begin{cases}
y' = f(x, y), \\
y(x_0) = y_0
\end{cases}
$$
has at least one solution $y(x)$ defined for $x$ in some open subinterval of $(a, b)$ that contains $x_0$.

# Uniqueness
In addition, if $\frac{\partial f}{\partial y}(x, y)$ is continuous on $\mathcal{R}$, then the solution is unique.
