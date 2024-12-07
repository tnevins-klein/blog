---
title: "Tensor"
date: 2024-09-26T21:40:34-04:00
draft: true
---
The set of **tensors** contains objects that in some sense "fully encapsulate" all maps on linear spaces.

**Rinehart's way** 
Let $V$ have finite dimension $n$.
$$V^* = \mathcal{L}(V,\mathbb{R})$$

**Theorem.** $V$ is naturally isomorphic to its "dual dual" $(V^*)^*$.
Define $\varphi : V \to V^{**}$ by $\varphi(v)\big(\omega\big) = \omega(v)$. 

$$V \otimes W = \{ f: V^* \times W^* \to \mathbb{R}\ \lvert \ f\text{ multilinear}\}$$

**Theorem.** $\mathcal{L}(V) \simeq V \otimes V^*$.

$$\mathcal{T}(m,n)= \{ S: \underbrace{V \times \cdots \times V}_{m \text{ times}} \times \underbrace{V^* \times \cdots \times  V^*}_{n \text{ times}} \to \mathbb{R}\ \lvert\ S \text{ multilinear} \}$$
