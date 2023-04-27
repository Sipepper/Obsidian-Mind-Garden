# Strong upper angle between geodesics
***
###### tags: #Geometry 
***
>[!dsn] Direct strict note
>Let $X$ be a metric space and let $c:[0,a]\to X$ and $c':[0,a']\to X$ be two geodesic paths with $c(0)=c'(0)=p$. The *strong upper angle* $\gamma$ between $c$ and $c'$ is the number $\gamma(c,c')\in[0,\pi]$ defined by:
>$$\gamma(c,c'):=\limsup_{s\to0;t\in(0,a']}\overline{\angle}_{p}(c(s),c'(t))=\lim_{\varepsilon}\sup_{s\in(0,\varepsilon];t\in(0,a']}\overline{\angle}_{p}(c(s),c'(t))$$.^[Martin R. Bridson, Andre Haefliger - "Metric spaces of non-positive curvature" p.11]

>[!example] 
>

#### Equivalence of angle definitions
>[!dsn] Direct strict note
>Let $X$ be a metric space. For all geodesics $c:[0,a]\to X$ and $c':[0,a']\to X$ with $c(0)=c'(0)$ one has $\angle(c,c')=\gamma(c,c')$.^[Martin R. Bridson, Andre Haefliger - "Metric spaces of non-positive curvature" p.11]

>[!proof]
>Let $p=c(0)=c'(0)$. It is clear from the definition that $\angle(c,c')\le\gamma(c,c')$. In order to establish the reverse inequality it suffices to show that for each fixed $t\in(0,a']$ we have $\limsup_{s\to0}\overline{\angle}_{p}(c(s),c'(t))\le\angle(c,c')$. For this we use the lemma [[Bounds for cosine of strong angle between geodesics]]. From which we have that $\liminf_{s\to0}\cos\gamma_{s,t}=\liminf_{s\to0}\frac{t-u_{s,t}}{s}$ for each fixed $t\in(0,a']$. If $t'<t$ then by the triangle inequality $t-t'\ge u_{x,t}-u_{s,t}$, and hence $t'-u_{s,t'}\le t-u_{s,t}$. Therefore
>$$\liminf_{s,t'\to0}\cos\gamma_{s,t'}\le\liminf_{s\to0}\cos\gamma_{s,t}$$
>The left hand side of this inequality is equal to $\cos\angle(c,c')$, so since $\cos$ is decreasing on$[0,\pi]$ we have $\limsup_{s\to0}\overline{\angle}_{p}(c(s),c'(t))\le\angle(c,c')$ for each $t\in(0,a']$, as required.
***
#### Keywords
- [[Metric space]],
- [[Geodesic path in metric space]],
- [[Angle between the geodesic paths]],
- [[Supremum and infinum]],
- [[Law of cosines in the euclidean space]],
- [[Comparison triangle]]
#### Possibly related
- 
***
#### Sources: