---
lesson: 2
title: Logistic (or Sigmoid) function
---

## {{ page.title }}

### What it does

- Calcula hipótese ($ h_\theta (x) $) em problemas de classificação.
- O resultado é sempre $ 0 \leq h_\theta (x) \leq 1 $.

### Math Formula
$$
h_\theta (x) = g(\theta^T x) = \dfrac{1}{1 + e^{-(\theta^T x)}} 
$$

### Octave Snippet
``` octave
x = [1 2]
theta = zeros(2, 1);
h = 1 / 1 + -(theta' * x);
```