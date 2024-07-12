---
{"dg-publish":true,"permalink":"/heaviside-function/"}
---

$$
u(t - \tau) = 
\begin{cases}
0 & \textit{if} & t < \tau \\
1 & \textit{if} & t \geq \tau \\
\end{cases}
$$
![Screenshot 2023-04-26 at 7.15.05 PM.png](/img/user/_attachments/Screenshot%202023-04-26%20at%207.15.05%20PM.png)

## Theorem (Translation in $t$)

Let $F(s) = \mathscr{L} \{f(t) \}$ and assume $\tau > 0$.

Then
$$
\mathscr{L} \{ u (t - \tau) f (t - \tau) \} = e^{-\tau s} F(s)
$$

and so $u(t - \tau) f(t - \tau) = \mathscr{L}^{-1} \{e^{-\tau s} F(s)\}$

Special Case: 
$$
f(t) = 1
\implies
\mathscr{L}\{u(t - \tau) \} = \frac{e^{-\tau s}}{s}
$$

