---
{"dg-publish":true,"permalink":"/euler-s-method/"}
---

- Find slope of solution at initial condition $(x_0, y(x_0))$ using ODE
- Make small line segment with slope $y'(x_0)$
- Take endpoint of line segment $(x_1, y_1)$ and use to find ODE again

TL;DR take a small line p_0 to p_1 with slope at p_0, make a new line p_1 to p_2 starting at p_1 with slope at p_1, etc...

## Problems
- Gets more inaccurate the further we are away from the starting point
