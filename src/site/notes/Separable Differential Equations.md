---
{"dg-publish":true,"permalink":"/separable-differential-equations/"}
---


In the form
$$
y' = g(x) h(y)
$$

Alternatively,
$$
\frac{dy}{dx} = f(x, y); f(x, y) = h(x) g(y)
$$

Eg: 
$y' = xy$
$y' = x^2$
$y' - xy = x \to y' = x(y+1)$

Not SDE: 
$y' = x^2 + y^2$

1. Constant solutions: $h(y) = 0$
	- $y' = F(-x, y)$
	- $F(x, a) = 0$ for all x
	- $y = a$ is a constant solution
2. Non-constant solutions:
$$
\begin{align}
\frac{dy}{dx} &= g(x) h(y) \\
\frac{dy}{h(y)} &= g(x) dx \\
\int \frac{dy}{h(y)} &= \int g(x) dx + c
\end{align}
$$

# Solution Technique
1. Rewrite as $\frac{1}{g(y)} dy = h(x) dx$ (provided $g(y) \neq 0$)
2. Integrate both sides

Implicit check:
1. Implicitly differentiate both sides
2. Rearrange for $y'$
3. Verify that it matches the original ODE
See also: [[Implicit Differentiation\|Implicit Differentiation]]


[[Applications of Separable ODEs\|Applications of Separable ODEs]]