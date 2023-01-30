---
{"dg-publish":true,"permalink":"/finite-state-processes/"}
---

- Models processes as a sequence of actions
- Algebraic form
- AKA [[Communicating Sequential Processes\|Communicating Sequential Processes]], [[Processes in Process Algebras\|Processes in Process Algebras]]

Repetition requires recursion
The following statements are equivalent

```
SWITCH = OFF,
OFF    = (on -> ON),
ON     = (off -> OFF).
```

```
SWITCH = OFF,
OFF    = ((on -> off) -> OFF).
```

```
SWITCH = (on -> off -> SWITCH).
```

