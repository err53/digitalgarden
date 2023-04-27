---
{"dg-publish":true,"permalink":"/dirac-delta-function/"}
---


The Dirac Delta Function at $t_0, \delta(t-t_0)$, is defined by the property
$$
\int_0^\infty f(t) \delta(t - t_0) dt = f(t_0)
$$

for any continuous function $f(t)$.

$\delta$ is not a function, but more of a general object called a [[Distribution\|Distribution]]

Thus,
$$
\begin{align}
\mathscr{L}\{f(t) \delta(t - t_0)\} &= \int_0^\infty e^{-st} f(t) \delta(t - t_0) dt \\
&= e^{-st_0} f(t_0)
\end{align}
$$

Corollary:
- $\mathscr{L}\{\delta(t-t_0)\} = e^{-st_0}$
- $\mathscr{L}\{\delta(t)\} = 1 \quad (t_0 = 0)$
