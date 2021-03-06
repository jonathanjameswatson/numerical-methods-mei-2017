---
title: Bisection method
order: 5
---

The bisection method is a numerical method used for finding the roots of an equation.

$$
\text{One root of } f(x) = x^6 + 4x - 3 \text{ is } \alpha \text{.}
$$

$$
\text{Find } \alpha \text{ where } 0 < \alpha < 1 \text{.}
$$

By considering whether or not a change of sign will occur, finding the value halfway between the boundaries will allow you to move one boundary and half the range of possible values for $\alpha$.

<sketch name="bisection" play></sketch>

A table can be made to demonstrate this process.

$$
\begin{array}{|c|c|c|c|c|c|c|}
\hline
a & f(a) & b & f(b) & c & f(c) & \text{Max |abs error| for } c \\ \hline
0 & -3 & 1 & 2 & 0.5 & -0.984 & 0.5 \\ \hline
0.5 & -0.984 & 1 & 2 & 0.75 & 0.178 & 0.25 \\ \hline
0.5 & -0.984 & 0.75 & 0.178 & 0.625 & -0.440 & 0.125 \\ \hline
\end{array}
$$

In the above table, $c$ is moved so that $f(a)$ is always negative and $f(b)$ is always positive.
