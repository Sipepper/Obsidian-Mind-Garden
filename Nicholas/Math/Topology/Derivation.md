---
Last time checked: 2023-10-19
Complete: false
aliases:
---
# Derivation
***
###### tags: #Topology/Differential 
***
>[!dsn]+ Definition
>Let $a\in\mathbb{R}^{n}$, a map $w:C^{\infty}\to\mathbb{R}$ is called a *derivation at $a$* if it is linear over $\mathbb{R}$ and satisfies the following product rule:
>$$w(fg)=f(a)wg+g(a)wf$$

>Derivations, is a more general variant of directional derivatives, i.e.
>$$D_{v}|_{a}f=D_{v}f(a)=\frac{d}{dt}\Bigg|_{t=0}f(a+tv)$$
>or 
>$$D_{v}|_{a}f=v^{i}\frac{\partial f}{\partial x^{j}}(a)$$
>as they have same properties as the derivations.
>>[!proof]+
>>.^[[[John M. Lee - Introduction to smooth manifolds.pdf#page=71 |John M. Lee - "Introduction to smooth manifolds" p.53 ]]]

>Suppose $a\in\mathbb{R}^{n}$, $w\in T_{a}\mathbb{R}^{n}$, and $f,g\in C^{\infty}(\mathbb{R}^{n})$, then
>1. If $f$ is a constant function, then $wf=0$.
>2. If $f(a)=g(a)=0$, then $w(fg)=0$.
>
>>[!proof]+
>>1. If suffices to prove for the constant function $f_{1}\equiv1$, for then $f(x)\equiv c$ implies
>>   $$wf=(w(cf_{1}))=cwf_{1}=0$$
>>   by linearity. For $f_{1}$, the product rule gives
>>   $$wf_{1}=w(f_{1}f_{1})=f_{1}(a)wf_{1}+f_{1}(a)wf_{1}=2wf_{1}$$
>>   which implies that $wf_{1}=0$.
>>2. Similarly, by the product rule
>>   $$w(fg)=f(a)wg+g(a)wf=0+0=0$$

>[!example]+ 
>
***
#### Keywords
- [[Function(mapping)]],
- [[Linear map]],
- [[Real line]],
- [[Directional derivative]],
- [[Function derivative]],
- [[Tangent vector]],
- [[Smooth function]],
- [[Euclidean space]]
#### Possibly related
- 
***
#### Sources: