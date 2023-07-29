---
title: "Reinventing a (Mathematical) Wheel"
date: 2023-07-29T09:02:40-04:00
---

I woke up this morning thinking about vector spaces. If that puts you off, this post is not for you. Sorry, Lin. Hello, Stocke.

I had read some [Dummit and Foote](https://www.amazon.com/Abstract-Algebra-3rd-David-Dummit/dp/0471433349) from a dubiously sourced PDF the night prior, and my mind was spinning. After stumbling to my shelf and getting a copy of [Axler](https://linear.axler.net/), I start messing with an integral that defines an inner product on the vector space of polynomials, $\mathcal{P}(x)$.
$$\langle p, q\rangle = \int_0^\infty p(x)q(x) e^{-x} dx,\quad p,q\in \mathcal{P}(x)$$
By the linearity of the integration operator:
$$\begin{align*}
&\int_0^\infty (a_nx^n + \cdots + a_0x^0) e^{-x} dx \\\\= a_n &\int_0^\infty x^n e^{-x} dx + \cdots + a_0 \int_0^\infty x^0 e^{-x} dx
\end{align*}$$

Something about that $\int_0^\infty x^n e^{-x}$ seems kind of familiar, no? I didn't think so. So I proceeded, taking care to integrate by parts and evaluate my limits properly,

$$\begin{align*}\int_0^\infty x^n e^{-x} dx = -x^ne^{-x} \Bigr]_0^\infty + n \int_0^\infty x^{n-1} e^{-x}dx\\\\\implies \int_0^\infty x^{n+1} e^{-x} dx = n \int_0^\infty x^n e^{-x} dx \\\\\end{align*}$$

What a fascinating relationship! I wonder what happens when we consider that integral as a function of $n$? Maybe we should give it a name? (spoiler: [$\Gamma(n)$](https://en.wikipedia.org/wiki/Gamma_function) seems like good a name as any).

I then proceeded to spend the next *20 minutes* checking my work and investigating the properties of this strange new function. It was when I began an induction proof that this mysterious function was equal to $n!$ for integers that it dawned on me what I was doing.

Lesson learned: don't do math sleep deprived. One connection trumps a dozen messy computations.
