# Curve in metric space
***
###### tags: #Geometry #Fundamental_math_objects 
***
>[!dsn] Direct strict note
>Let $X$ be a metric space. A *curve* or a *path* in $X$ is a *continuous* map $c$ from a compact interval $[a,b]\subset\mathbb{R}$ to $X$.
>We say that $c$ joins the pont $c(a)$ to the pont $c(b)$.^[Martin R. Bridson, Andre Haefliger - "Metric spaces of non-positive curvature" p.12 ]

>If $c_{1}:[a_{1},b_{1}]\to X$ and $c_{2}:[a_{2},b_{2}]\to X$ are two paths such that $c_{1}(b_{1})=c_{2}(a_{2})$, their *concatenation* is the path $c:[a_{1},b_{1}+b_{2}-a_{2}]\to X$ defined by $c(t)=c_{1}(t)$ if $t\in[a_{1},b_{1}]$ and $c(t)=c_{2}(t+a_{2}-b_1)$ if $t\in[b_{1},b_{1}+b_{2}-a_{2}]$. Concatenation can be inductively generalised to be applied to a finite sequence of paths.

>[!example] 
>Let $(X,d)=C(\mathbb{R})$ with "area metric", we can define a curve in $(X,d)$ as follows, let $e^{-ax^{2}}$ be a family of "bell curves" parametrized by real positive numbers. Then $c:[1,12]\to C(\mathbb{R})$ is a continuous map of the compact interval $[1,12]$ to a $C(\mathbb{R})$ space, therefore is a curve.  
***
#### Keywords
- [[Metric space]],
- [[Continuous mapping]],
- [[Interval]],
- [[Compact subsets of a metric space]],
- [[Compact set]],
- [[Mathematical induction]],
- [[Space of all continuous functions on the interval]],
- [[Real line]]
#### Possibly related
- 
***
#### Sources: