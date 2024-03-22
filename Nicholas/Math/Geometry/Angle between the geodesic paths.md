---
Last time checked: 2024-02-15
Complete: false
aliases:
---
# Angle between the geodesic paths
***
###### tags: #Geometry 
***
>[!dsn]+ Definition
>Let $X$ be a metric space and let $c:[0,a]\to X$ and $c':[0,a']\to X$ be two geodesic paths with $c(0)=c'(0)$. Given $t\in(0,a]$ and $t'\in(0,a']$, we consider the comparison triangle $\overline{\Delta}(c(0),c(t),c'(t'))$, and the comparison angle $\overline{\angle}_{c(0)}(c(t),c'(t'))$. The (Alexandrov) *angle* or the *upper angle* between the geodesic paths $c$ and $c'$ is the number $\angle(c,c')\in[0,\pi]$ defined by
>$$\angle(c,c'):=\limsup_{t,t'\to0}\overline{\angle}_{c(0)}(c(t),c'(t'))=\lim_{\varepsilon\to0}\sup_{0<t,t'<\varepsilon}\overline{\angle}_{c(0)}(c(t),c'(t'))$$
>.^[[[Martin R. Bridson, Andrea Haefliger - Metric spaces of non-positive curvature.pdf#page=28|Martin R. Bridson, Andrea Haefliger - "Metric spaces of non-positive curvature" p.9]]]

>If the limit $\lim\limits_{t,t'\to0}\overline{\angle}_{c(0)}(c(t),c'(t))$ exists, then we say the *angle exists in the strict sense*.

>We can express $\angle(c,c')$ purely in terms of the distance function by noting that 
>$$\cos(\overline{\angle}_{c(0)}(c(t),c'(t')))=\frac{1}{2tt'}\left(t^{2}+t'^{2}-d(c(t),c'(t'))^{2}\right)$$
>by law of cosines.

>[!example]
>Consider $(\mathbb{R}^{2},d_{\infty})$, where $d_{\infty}((x,y),(x',y')):=\max\set{|x-x'|,|y-y'|}$. For every integer $n>1$, the map $t\mapsto(t,[t(1-t)^{n}])$ defines a geodesic path $[0,1/n]\to(\mathbb{R}^{2},d_{\infty})$. These geodesics all issue from a common point and their germs are pairwise disjoint, but the angle between any two of them is zero.

#### Properties
- The angle between $c$ and $c'$ depends only on the germs of these paths at $0$: if $c'':[0,l]\to X$ is any geodesic path for which there exists $\varepsilon>0$ such that $c''|_{[0,\varepsilon]}=c'|_{[0,\varepsilon]}$, then the angle between $c$ and $c''$ is the same as that between $c$ and $c'$.
- In a metric tree, the angle between two geodesic segments which have a common endpoint is either $0$ or $\pi$.
- $\limsup$ is essential in definition, because the limit in general case does not exist.
- The angle between the incoming and outcoming germs of a geodesic at any interior point along its image is $\pi$. In other words, if $c:[a,b]\to X$ is a geodesic path with $a<0<b$, and if we define $c':[0,-a]\to X$ and $c'':[0,b]\to X$ by $c'(t)=c(-t)$ and $c''(t)=c(t)$, then $\angle(c',c'')=\pi$.
- Angle between disticnt geodesics issuing from the same point may be $0$, even if their germs are distinct. Thus, in general, $(c,c')\mapsto\angle(c,c')$ does not define a metric on the set of geodesics issuing from a point.
***
#### Keywords
- [[Metric space]],
- [[Interval]],
- [[Geodesic path in metric space]],
- [[Comparison triangle]],
- [[Supremum and infinum]],
- [[Upper and lower limit]],
- [[Law of cosines in the euclidean space]],
- [[Euclidean space]],
- [[Tree]]
#### Possibly related
- 
***
#### Sources: