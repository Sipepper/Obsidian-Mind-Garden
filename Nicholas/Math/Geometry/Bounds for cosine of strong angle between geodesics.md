# Bounds for cosine of strong angle between geodesics
***
###### tags: #Geometry 
***
>[!dsn] Direct strict note
>Let $(X,d)$ be a metric space. For all geodesics $c:[0,a]\to X$ and $c':[0,a']\to X$ let $u_{s,t}=d(c(s),c'(t))$ and let $\gamma_{s,t}=\overline{\angle}_{p}(c(s),c'(t))$. Then
>$$\frac{t-u_{s,t}}{s}\le\cos\gamma_{s,t}\le\frac{t-u_{s,t}}{s}+\frac{s}{2t}$$.^[Martin R. Bridson, Andre Haefliger - "Metric spaces of non-positive curvature" p.11]

>[!proof]
>From the definition of $\gamma_{s,t}$ we have
>$$\cos\gamma_{s,t}=\frac{s^{2}+t^{2}-u_{s,t}^{2}}{2st}=\frac{t-u_{s,t}}{s}+\frac{s^{2}-(u_{s,t}-t)^{2}}{2st}$$
>And by the triangle inequality $|u_{s,t}-t|\le s$, whence $0\le\frac{s^{2}-(u_{s,t}-t)^{2}}{2st}\le\frac{s}{2t}$

>[!example] 
>
***
#### Keywords
- [[Metric space]],
- [[Geodesic path in metric space]],
- [[Comparison triangle]],
- [[Law of cosines in the euclidean space]],
#### Possibly related
- 
***
#### Sources: