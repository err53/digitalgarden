---
{"dg-publish":true,"permalink":"/automata/"}
---

[[Alphabet\|Alphabet]]

There are a set of **states** $Q$. If it's finite, then it's a [[Finite State Machine\|Finite State Machine]]
There are a set of **actions/operations** that allow from moving between states.
There is a **transition function/relation** that allow movement between states using actions/operations

Deterministic Automation is a 5-tuple
$$M = (\Sigma, Q, \delta, s_o, F)$$
where: $\Sigma$ is the **alphabet**
$Q$ is the set of states
$\delta: Q \times \Sigma \to Q$ is **transition function**
$s_0 \in Q$ is the **initial state**
$F \subseteq Q$ is the set of **final states**

Deterministic means that the next transition is predetermined (always known) given the current state

[[Finite State Automata\|Finite State Automata]]

See also: [[NieR Automata\|NieR Automata]]