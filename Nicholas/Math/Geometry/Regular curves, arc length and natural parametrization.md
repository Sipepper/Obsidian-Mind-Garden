---
Last time checked: 2024-02-11
Complete: true
aliases:
---
# Regular curves, arc length and natural parametrization
***
###### tags: #Geometry/Differential 
***
#### Regular curve
>[!dsn]+ Definition
>A parameterized differentiable curve $\alpha:I\to\mathbb{R}^{n}$ is said to be *regular* if $\alpha'(t)\ne0$, for all $t\in I$.^[Manfredo P. do Carmo - "Differential Geometry of Curves and Surfaces" p.6]

>[!example]+
>Let $\alpha(t)=(\cos(t),\sin(t),t)$, it's tangent $\alpha'(t)=(-\sin(t),\cos(t),1)$ for all $t\in I$ is not zero.

#### Arc length
>[!dsn]+ Definition
>Let $t_{0}\in I$, *arc length* of a regular parameterized curve $\alpha:I\to\mathbb{R}^{n}$, from point $t_{0}$, is a following integral
>$$s(t)=\int_{t_{0}}^{t}\|\alpha'(s)\|ds$$
>where
>$$\|\alpha'(s)\|=\sqrt{\left(x'_{1}(s) \right)^{2}+\left(x'_{2}(s) \right)^{2}+\dots+\left(x'_{n}(s) \right)^{2}}$$
>is a length of tangent vector $\alpha'(t)$. As $\alpha'(t)\ne0$, arc length $s$ is a differentiable map by $t$ and $\frac{ds}{dt}=\|\alpha'(t)\|$.^[Manfredo P. do Carmo - "Differential Geometry of Curves and Surfaces" p.6]

>[!example]+ 
>Let $\alpha(t)=(t^{2},t+1,e^{t})$ then for $t\in[-1,1]$:
>$$s(t)=\int_{-1}^{1}\|\alpha'(t)\|dt=\int_{-1}^{1}\sqrt{4t^{2}+1+e^{t}}dt\approx3.6685$$

#### Natural parameterization
>[!dsn]+ Definition
>Sometimes parameter $t$ corresponds exactly to the arclength. In such case $\frac{ds}{dt}=1=\|\alpha'(t)\|$; that is, velocity vector is a unit vector, i.e. $\|\alpha'(t)\|\equiv1$. Conversely if $\alpha'(t)\equiv1$, then
>$$s=\int_{t_{0}}^{t}dt=t-t_{0}$$
>i.e. $t$ is a length of an arc segment of $\alpha$ measured from some point. Such parameterization is often called the *natural parameterization*.^[Manfredo P. do Carmo - "Differential Geometry of Curves and Surfaces" p.6]

>[!example]+
>Let $\alpha(t)=(a\cos(t),a\sin(t))$, which defines a circle with radius $a$ at coordinate origin on a plane. Then arc length of an arbitrary segment can be computed as follows
>$$s(t)=\int_{t_{0}}^{t}\sqrt{a^{2}}ds=\|a\|(t-t_{0})$$
>note that if we change parameter $t$ to $t/a$ then
>$$s(t)=\int_{t_{0}}^{t}\sqrt{a^{2}\frac{1}{a^{2}}}ds=(t-t_{0})$$
>thus $t/a$ is a natural parameterization.
***
#### Keywords
- [[Parametrized differentiable curve in euclidean space]],
- [[Tangent vector]],
- [[Euclidean space]],
- [[Trigonometric functions]],
- [[Function derivative]],
- [[Function(mapping)]],
- [[Riemann integral]]
#### Possibly related
- 
***
#### Sources: