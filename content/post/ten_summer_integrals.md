---
title: "3+ Summer Integrals"
date: 2023-07-26T14:15:59-06:00
---

Last year, with grueling effort and a little help from my friend [Stewie](https://www.amazon.com/Calculus-Early-Transcendentals-James-Stewart/dp/1285741552), I managed to complete my school's Calculus I and II courses. Those classes were perhaps the best math classes I've ever taken, seamlessly weaving intuition with elegant formalism ($\delta$-$\varepsilon$ proofs, anyone?). While my summer math efforts have included tours of number theory, combinatorics, the thing that I have spent perhaps the most time on is evaluating integrals.

The process of evaluating integrals encapsulates everything I love about math: a perfect balance of carefully woven principles and ingenuity. In this post, I would like to present my 3 favorite integrals I've come across these past few months, arranged approximately in ascending order of difficulty.

### 1. A simple, Fourier-adjacent integral
$$ \int_0^1 \cos(n\pi x) \sin(m \pi x) dx\quad m, n \in \mathbb{Z} $$
I first came across this integral towards the end of the school year, and may be the first "challenge" integral I ever evaluated. After much thought, I managed to rederive the half-remembered product-to-sum identities, and reduce it to a relatively simple form. The part I found tricky at the end was coming up with a closed form expression.

### 2. A fun series integral
$$ \int_0^1 \left( \sum_{n = 1}^\infty \frac{\lfloor 2^n x \rfloor}{3^n} \right)^2 dx $$
I believe this originally comes from an MIT integration bee problem. I dare not spoil the fun, but it is very helpful to note that $\int_0^1 = \int_0^\frac12 + \int_\frac12^1$.

### 3. Huh?
$$ \int_1^\infty \left\\{ \frac{1}{x} \right\\} dx  $$

where $\\{x\\}$ is the [fractional part function](https://en.wikipedia.org/wiki/Fractional_part).

### Bonus: a really hard one
$$ \int_{-\infty}^\infty \frac{\log \left| \zeta (1/2 + it) \right|}{1 + 4t^2} dt $$

Email me if you solve this one.
