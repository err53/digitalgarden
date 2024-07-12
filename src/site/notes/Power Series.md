---
{"dg-publish":true,"permalink":"/power-series/"}
---

# Power Series

In the form

$$
\sum_{n=0}^\infty C_n (x-a)^n
$$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/radius-of-convergence/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




## Radius of Convergence
Represented as either a nonnegative real number or $\infty$ such that the series converges if $|x - a| < r$, and diverges if $|x - a| > r$. At $|x - a| = r$, the series may or may not converge.

Thus,
$
\begin{align}
a - r < x < a + r &\hspace{2em} \text{power series converges} \\
x < a - r\ \operatorname{and}\ x > a + r &\hspace{2em} \text{power series diverges}
\end{align}
$

## Alt Definition
In other words, given a power series $\sum_{n=0}^\infty c_n (x - x_0)^n$ centred at $x_0$, there exists a number R with $0 \leq R \leq \infty$ called the radius of convergence.
- The series converges absolutely if $|x - x_0| < R$
- The series diverges if $|x - x_0| > R$



</div></div>


## Random Things of Note

In the case of $x = a$, the power series will always converge
Generally, using the [[Ratio Test\|Ratio Test]] or [[Root Test\|Root Test]] will be most successful