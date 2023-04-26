---
{"dg-publish":true,"permalink":"/voltera-integral-equation/"}
---

Equation of the form
$$
\begin{align}
f(t) &= g(t) + (f* h)(t), t \geq 0 \\
&= g(t) + \int_0^t f(t - \tau) h(\tau) d \tau
\end{align}
$$

Where $g(t)$ and $h(t)$ are given function.

Use the [[Laplace Transform\|Laplace Transform]] with [[Convolution\|Convolution]] to solve it

## Steps
- Take Laplace of both sides
- Calculate specific Laplace of $f()$ and $h()$
- Reduce down to functions of $F(s) = \mathscr{L}(t)$
- Isolate for $F(s)$
- Perform [[Partial Fraction Decomposition\|Partial Fraction Decomposition]]
- Take [[Inverse Laplace Transform\|Inverse Laplace Transform]]

