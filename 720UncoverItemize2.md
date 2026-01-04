---
author:
- Bert
title: A tale of N primes
---

::: frame
:::

::: frame
Definition and Examples

- **Definition:** An interval is a set of real numbers

- **Notation:** We use brackets and parentheses

- **Examples:**

<!-- -->

- $[a,b]$

- $(a,b)$

- $(a, \infty)$
:::

::: frame
More Examples

- $[0, 1] = \{x : 0 \leq x \leq 1\}$

- $(-1, 2) = \{x : -1 < x < 2\}$

- $(3, \infty) = \{x : x > 3\}$

- $(-\infty, 0] = \{x : x \leq 0\}$

- $(0, 1] = \{x : 0 < x \leq 1\}$

- $[-2, 2) = \{x : -2 \leq x < 2\}$
:::

::: frame
Properties

- **Intersection:** $[a,b] \cap [c,d] = [\max(a,c), \min(b,d)]$

- **Union:** Not always an interval

- **Length:** $\text{length}([a,b]) = b - a$

- **Center:** $\text{center}([a,b]) = \frac{a+b}{2}$

- **Subset:** If $a \leq c \leq d \leq b$, then $[c,d] \subseteq [a,b]$
:::

::: frame
Graphical Representation **On the real line:**

- Closed endpoint: $\bullet$

- Open endpoint: $\circ$

- Infinite: $\rightarrow$ or $\leftarrow$

**Examples:**

- $[1,3]$: $\bullet$$---$$\bullet$

- $(1,3)$: $\circ$$---$$\circ$

- $(2,\infty)$: $\circ$$\rightarrow$

- $(-\infty,1]$: $\leftarrow$$\bullet$
:::

:::: frame
Applications - Solving Inequalities

::: block
Example 1 Solve: $2x - 3 < 5$
:::

- $2x - 3 < 5$

- $2x < 8$

- $x < 4$

- Solution: $(-\infty, 4)$
::::

:::: frame
Applications - Set Operations

::: block
Example 2 Find: $[-1, 3] \cap (2, 5)$
:::

- $[-1, 3] = \{x : -1 \leq x \leq 3\}$

- $(2, 5) = \{x : 2 < x < 5\}$

- Intersection: $\{x : 2 < x \leq 3\}$

- Result: $(2, 3]$
::::

:::: frame
Applications - Function Domains

::: block
Example 3 Find domain of: $f(x) = \sqrt{4 - x^2}$
:::

- Need: $4 - x^2 \geq 0$

- $x^2 \leq 4$

- $-2 \leq x \leq 2$

- Domain: $[-2, 2]$
::::

::: frame
Important Theorems

- **Intermediate Value Theorem:** If $f$ continuous on $[a,b]$, takes
  all values between $f(a)$ and $f(b)$

- **Extreme Value Theorem:** Continuous on $[a,b]$ $\Rightarrow$ attains
  max and min

- **Mean Value Theorem:** If $f$ differentiable on $(a,b)$,
  $\exists c \in (a,b)$ with: $$f'(c) = \frac{f(b)-f(a)}{b-a}$$
:::

::: frame
Summary

- Intervals: sets of real numbers

- Notation: $[$ for included, $($ for excluded

- Types: closed, open, half-open, infinite

- Properties: intersection, length, center

- Applications: inequalities, domains, theorems

- Graphical: $\bullet$, $\circ$, $\rightarrow$

- Fundamental in real analysis

- Essential for calculus

- Basis for advanced mathematics
:::
