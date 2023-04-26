---
{"dg-publish":true,"permalink":"/convolution/"}
---

Convolution of $f(t)$ and $g(t)$ denoted $(f * g) (t)$ is
$$
(f*g) (t) = \int_0^t f(t-\tau) g(\tau) d \tau = \int_0^t f(-(\tau - t))g(\tau)d\tau
$$

## Properties
### Commutativity
$f * g = g * f$

### Distributivity
$f * (g + h) = (f * g) + (f * h)$

### Associativity
$(f*g)*h = f*(g*h)$

### Zero
$f * 0 = 0$

## Theorem
If $f(t)$ and $g(t)$ are piecewise continuous and of exponential order for $t \geq 0$, then so is $(f * g)(t)$ and
$$\mathscr{L}\{f * q \} = F(s) G(s)$$ where $F(s) = \mathscr{L}\{f\}$ and  $G(s) = \mathscr{L}\{g\}$

## Voltera Integral Equation

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/voltera-integral-equation/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




Equation of the form
$
\begin{align}
f(t) &= g(t) + (f* h)(t), t \geq 0 \\
&= g(t) + \int_0^t f(t - \tau) h(\tau) d \tau
\end{align}
$

Where $g(t)$ and $h(t)$ are given function.

Use the [[Laplace Transform\|Laplace Transform]] with [[Convolution\|Convolution]] to solve it

## Steps
- Take Laplace of both sides
- Calculate specific Laplace of $f()$ and $h()$
- Reduce down to functions of $F(s) = \mathscr{L}(t)$
- Isolate for $F(s)$
- Perform [[Partial Fraction Decomposition\|Partial Fraction Decomposition]]
- Take [[Inverse Laplace Transform\|Inverse Laplace Transform]]



</div></div>
