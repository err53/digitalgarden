---
{"dg-publish":true,"permalink":"/exact-ode/"}
---

Of the form
$$
M(x, y) dx + N(x, y)dy = 0
$$
If a function $F(x, y)$ exists such that total differential $dF$ satisfies
$dF = M(x, y) dx + N(x, y) dy$, then the ODE is exact.

In other words, if $\frac{\partial M}{\partial y}$ and $\frac{\partial N}{\partial x}$ are both continuous functions of $x$ and $y$ on some open set $S$, then the ODE is **exact** on S iff $\frac{\partial M}{\partial y} = \frac{\partial N}{\partial x}$


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/ode-exact-equation-theorem/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




Theorem:

Given an ODE in the form of $M(x, y) dx + N(x y) dy = 0$

If $\frac{\partial M}{\partial y}$ and $\frac{\partial N}{\partial x}$ are constants in x and y on an open set S,
then this ODE is ==exact on S== iff $\frac{\partial M}{\partial y} = \frac{\partial N}{\partial x}$

$
dF = \frac{\partial F}{\partial x} dx + \frac{\partial F}{\partial y} dy
$
with the goal to find such an $F$


</div></div>


## Solving an Exact ODE
1. Determine that the ODE is exact: $\frac{\partial M}{\partial y} = \frac{\partial N}{\partial x}$
2. Try to find $F(x, y)$ such that $$ dF = \frac{\partial F}{\partial x}dx + \frac{\partial F}{\partial y}dy = M(x, y) dx + N(x, y)dy$$
3. Integrate $\frac{\partial F}{\partial x} = M(x, y)$ wrt $x$, thinking of $y$ as a constant: $$ F(x, y) = \int M(x, y) dx + B(y)$$
4. Differentiate this w.r.t $y$ to find function $B(y)$ from: $$N(x, y) = \frac{\partial F}{\partial y} = \frac{\partial}{\partial y}\left(\int M(x, y) dx\right) + B'(y)$$
5. The solution is $F(x, y) = C$, where $C$ is an arbitrary constant

## Finding an Integrating Factor

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/integrating-factor-for-second-order-od-es/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




## Definition
If there is a function $\mu(x, y)$ such that

$
\mu(x, y) M(x, y) dx + \mu(x, y) N(x, y) dy = 0
$
is exact, then $\mu(x, y)$ is an integrating factor

## Finding Integrating factor

Let $\frac{\partial f}{\partial x} = f_x$ and $\frac{\partial f}{\partial y} = f_y$

- Solve $\mu_y M + \mu M_y = \mu_x N + \mu N_x$
	- PDE, so generally hard to solve, simplify by assuming $\mu(x, y) = \mu(x)$ or $\mu(x, y) = \mu(y)$
- If we assume $\mu(x, y) = \mu(x)$, equation reduces to
$
\mu M_y = \mu_x N + \mu N_x \Longrightarrow \frac{d \mu}{dx} = \mu(x) \frac{M_y - N_x}{N}
$
- Assume, $\mu(x, y) = \mu(y)$, reduces to
$
\mu_y M + \mu M_y = \mu N_x \Longrightarrow \frac{d \mu}{dy} = \mu(y) \frac{N_x - M_y}{M}
$



</div></div>
