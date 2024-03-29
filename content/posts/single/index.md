+++
title = 'Single'
date = 2024-03-29T14:07:35+08:00
draft = false
math = 'katex'
+++


# Intro

my image:
![](anyname/1.png)

otherone:

{{ $image := .Resources.Get "anyname/1.png" }}

<img src="anyname/1.png" style="zoom:50%;" />

{{< figure src="anyname/1.png" title="Steve abc" width="300" height="400" >}}


# math

\[
\begin{aligned}
KL(\hat{y} || y) &= \sum_{c=1}^{M}\hat{y}_c \log{\frac{\hat{y}_c}{y_c}} \\
JS(\hat{y} || y) &= \frac{1}{2}(KL(y||\frac{y+\hat{y}}{2}) + KL(\hat{y}||\frac{y+\hat{y}}{2}))
\end{aligned}
\]




This is an inline \(a^*=x-b^*\) equation.

These are block equations:

\[a^*=x-b^*\]

\[ a^*=x-b^* \]

\[
a^*=x-b^*
\]

These are block equations using alternate delimiters:

$$a^*=x-b^*$$

$$ a^*=x-b^* $$

$$
a^*=x-b^*
$$