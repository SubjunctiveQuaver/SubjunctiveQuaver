# Why probability and statistics needs measure theory

## Introduction

You may have encountered continuous probability distributions such as the normal distribution. It's often used to model things in the real world, and has nice statistical properties. What you may not have seen is its *probability density function*: given $\theta = (\mu,\sigma^2) \in \Theta = \R \times (0,\infty)$,
$$f_\theta : \R \to \R, \quad x \mapsto \frac{1}{\sqrt{2\pi\sigma^2}}\exp\left(-\frac{(x - \mu)^2}{2\sigma^2}\right)$$
