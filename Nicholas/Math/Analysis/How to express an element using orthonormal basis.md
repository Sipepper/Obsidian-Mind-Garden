# How to express an element using orthonormal basis
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Direct strict note
>Let $H$ be a Hilbert space and let $S=\{u_{\alpha}\}_{\alpha\in L}$ be an otrthonormal basis. Then for all $v\in H$
>$$v=\sum\limits_{\alpha\in L}(u_{\alpha},v)_{H}v_{\alpha}$$
>and
>$$\|v\|_{H}^{2}=\sum\limits_{\alpha\in L}|(u_{\alpha},v)_{H}|^{2}$$
>.^[Fabio Silva Botelho - "Functional analysis and applied optimization in banach spaces" p.37-39]

>[!proof]+
>Let $L'$ be a finite subset of $L$. By [[Bessel's inequality]] we have that
>$$\sum\limits_{\alpha\in L'}|(u_{\alpha},v)_{H}|\le\|v\|_{H}^{2}$$
>Therefore we can conclude that a set $A_{n}=\{\alpha\in L:|(u_{\alpha},v)_{H}>1/n\}$ is finite, and thus
>$$A=\{\alpha\in L:|(u_{\alpha},v)_{H}|>0\}=\bigcup\limits_{n=1}^{\infty}A_{n}$$
>where $A$ is at most countable.
>
>Therefore $(u_{\alpha},v)_{H}\ne0$ for at most countable number of indices $\alpha\in L$, from which we form a sequence $\{\alpha_{n}\}_{n\in\mathbb{N}}$. Since the sequence
>$$s_{N}=\sum\limits_{i=1}^{N}|(u_{\alpha_{i}},v)_{H}|^{2}$$
>is monotonically increasing and bounded, it is converging to some real limit as $N\to\infty$. Define
>$$v_{n}=\sum\limits_{i=1}^{n}(u_{\alpha_{i}},v)_{H}u_{\alpha_{i}}$$
>so that for $n>m$ we have
>$$\begin{align}\|v_{n}-v_{m}\|_{H}^{2}&=\left\|\sum\limits_{i=m+1}^{n}(u_{\alpha_{i}},v)_{H}u_{\alpha_{i}}\right\|_{H}^{2}\\ &=\sum\limits_{i=m+1}^{n}|(u_{\alpha_{i}},v)_{H}|^{2}\\ &=|s_{n}-s_{m}|\end{align}$$
>Hence, $\{v_{n}\}$ is a Cauchy sequence which converges to some $v'\in H$.
>Observe that
>$$\begin{align}(v-v',u_{\alpha_{i}})_{H}&=\lim_{N\to\infty}\left(v-\sum\limits_{i=1}^{N}(u_{\alpha_{i}},v)_{H}u_{\alpha_{i}},u_{\alpha_{i}}\right)_{H}\\ &=(v,u_{\alpha_{i}})_{H}-(v,u_{\alpha_{i}})_{H}\\ &=0 \end{align}$$
>Also, if $\alpha\ne\alpha_{l}$, $\forall l\in\mathbb{N}$, then
>$$(v-v',u_{\alpha})_{H}=\lim_{N\to\infty}\left(v-\sum\limits_{i=1}^{\infty}(u_{\alpha_{i}},v)_{H}u_{\alpha_{i}}u_{\alpha}\right)_{H}=0$$
>Hence $v-v'\perp u_{\alpha}$, $\forall\alpha\in L$.
>If $v-v'\ne\theta$, then we could obtain an orthonormal set
>$$\{u_{\alpha}:\alpha\in L\}\cup\left\{\frac{v-v'}{\|v-v'\|_{H}} \right\}$$
>which would properly contain the complete orthonormal set $\{u_{\alpha}:\alpha\in L\}$, contradiction.
>Therefore, $v-v'=\theta$, that is,
>$$v=\lim_{N\to\infty}\sum\limits_{i=1}^{N}(u_{\alpha_{i}},v)_{H}u_{\alpha_{i}}$$

>[!example]+ 
>
***
#### Keywords
- [[Hilbert space]],
- [[Orthonormal basis]],
- [[Cardinality of a set]],
- [[Set]],
- [[Monotonicity]],
- [[Sequence]],
- [[Convergence in metric spaces]],
- [[Real line]],
- [[Cauchy sequence]]
#### Possibly related
- [[Bounded set]]
***
#### Sources: