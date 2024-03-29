+++
title = 'Hello Hugo'
date = 2024-03-29T14:07:35+08:00
draft = false
math = 'katex'
+++


# This is a title

This is a cute shibaInu image:
![](media/shibaInu.jpg)


# This is a second title

another resized one:

{{< figure src="media/shibaInu.jpg" title="Steve" width="300" height="200" >}}

another centered one:

{{< figure src="media/shibaInu.jpg" align=center >}}


## this is a subtitle 
 - math

This is a math block:

$$
\begin{aligned}
KL(\hat{y} || y) &= \sum_{c=1}^{M}\hat{y}_c \log{\frac{\hat{y}_c}{y_c}} \\
JS(\hat{y} || y) &= \frac{1}{2}(KL(y||\frac{y+\hat{y}}{2}) + KL(\hat{y}||\frac{y+\hat{y}}{2}))
\end{aligned}
$$


This is an inline \(a^*=x-b^*\) equation. 

This is another one with math symbols: $\phi = \pi$.

More block equations:

\[a^*=x-b^* \]
