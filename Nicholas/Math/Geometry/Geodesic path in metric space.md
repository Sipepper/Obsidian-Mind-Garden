---
Last time checked: 2024-02-10
Complete: false
aliases:
---
# Geodesic path in metric space
***
###### tags: #Geometry/Metric   
***
>[!dsn]+ Definition
>Let $(X,d)$ be a metric space. A *geodesic path* joining $x\in X$ to $y\in X$ is a map $c$ from a closed interval $[0,l]\subset\mathbb{R}$ to $X$ such that $c(0)=x$, $c(l)=y$ and $d(c(t),c(t'))=|t-t'|$ for all $t,t'\in[0,l]$.^[Martin R. Bridson, Andre Haefliger - "Metric spaces of non-positive curvature" c.]

>The image $\alpha$ of $c$ is called a *geodesic segment* with endpoints $x$ and $y$.

>[!example]+
>

#### Different types of geodesics
>[!dsn]+ Definition
>Let $I\subseteq\mathbb{R}$ be and interval. A map $c:I\to X$ is said to be a *linearly reparametrized geodesic* or a *constant speed geodesic*, if exists $\lambda$ such that $$d(c(t),c(t'))=\lambda|t-t'|\quad\forall t,t'\in I$$ c parametrizes its image *proportional to arc length*.

>[!example]+
>

>[!dsn]+ Definition
>A *geodesic ray* in $X$ is a map $c:[0,\infty)\to X$ such that $d(c(t),c(t'))=|t-t'|$ for all $t,t'\ge0$.

>[!example]+
>

>[!dsn]+ Definition
>A *geodesic line* in $X$ is a map $c:\mathbb{R}\to X$ such that $d(c(t),c(t'))=|t-t'|$ for all $t,t'\in\mathbb{R}$.

>[!example]+
>

>[!dsn]+ Definition
>A *local geodesic* in $X$ is a map $c$ from an interval $I\subset\mathbb{R}$ to $X$ with the property that for every $t\in I$ there exists $\varepsilon>0$ such that $d(c(t'),c(c''))=|t'-t''|$ for all $t',t''\in I$ with $|t-t'|+|t-t''|\le\varepsilon$.

>[!example]+
>
***
#### Keywords
- [[Metric space]],
- [[Function(mapping)]],
- [[Absolute value]],
- [[Real line]],
- [[Kernel and image of a mapping]],
- [[Interval]],
- [[Open and closed subsets]],
#### Possibly related
- [[Regular curves, arc length and natural parametrization]]
***
#### Sources: