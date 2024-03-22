---
Last time checked: 2024-01-20
Complete: false
aliases:
---
# Fundamental theorem of algebra 
***
###### tags: #Algebra  
***
>[!dsn]+ Theorem
>Every polynomial 
>$$f(z)=a_{n}z^{n}+a_{n-1}z^{n-1}+\dots+a_{1}z+a_{0}$$
>where $a_{i}$ are some complex non zero numbers, and $n\ge1$ has a solution; i.e. exists some complex number $z_{0}$ such that $f(z_{0})=0$.^[Sidney A. Morris - "Topology without tears" p.217]

>[!proof]+
>$$\begin{align}|f(z)|&=|a_{n}z^{n}+a_{n-1}z^{n-1}+\dots+a_{0}|\\ &\ge|a_{n}||z|^{n}-|z|^{n-1}\left(|a_{n-1}|+\frac{|a_{n-2}|}{|z|}+\dots+\frac{|a_{0}|}{|z|^{n-1}}\right)\\ &\ge|a_{n}||z|^{n}-|z|^{n-1}\left(|a_{n-1}|+|a_{n-2}|+\dots+|a_{0}|\right),\quad \{|z|\ge1\}\\ &=|z|^{n-1}\left(|a_{n}||z|-R\right)\ge|z|^{n-1}\qquad (1) \end{align}$$
>for $|z|\ge\max\left\{1,\frac{R+1}{|a_{n}|}\right\}$, where $R=|a_{n-1}|+\dots+|a_{0}|$. Put $p_{0}=|f(0)|=|a_{0}|$ then, from inequality above we see that exist some number $T>0$ such that $$|f(z)|>p_{0},\quad\forall z,|z|>T\quad(2)$$
>Now consider the set $D=\set{z:z\in\mathbb{C},|z|\le T}$. It's a closed bounded region of a complex plane, because [[Complex plane is homeomorphic to a real plane]], and thus by [[Heine-Borel theorem]] is compact. Therefore by [[Continuous image of compact set to a real line has least and greatest elements]], continuous function $|f|:D\to\mathbb{R}$ has least value in some point $z_{0}$, from that we get an inequality $$|f(z_{0})|\le|f(z)|,\quad\forall z\in D$$ From $(2)$ for $z\notin D$, $|f(z)|>p_{0}=|f(0)|\ge|f(z_{0})|$. Thus $$|f(z_{0})|\le|f(z)|,\quad z\in\mathbb{C}\quad(3)$$ Therefore only thing we need to show is that $f(z_{0})=0$. To do that we will perform a "shift". Let $P(z)=f(z+z_{0})$. Then from $(2)$ follows $$|P(0)|\le|P(z)|,\quad\forall z\in\mathbb{C}\quad(4)$$ Now our problem is to shifted from showing that $f(z_{0})=0$ to showing that $P(0)=0$.
>
>Now $P(z)=b_{n}z^{n}+b_{n-1}z^{n-1}+\dots+b_{0}$,$b_{i}\in\mathbb{C}$. Therefore $P(0)=b_{0}$. Let's show that, $b_{0}=0$.
>Suppose the contrary, that $b_{0}\ne0$. Then $$P(z)=b_{0}+b_{k}z^{k}+z^{k+1}Q(z)\quad(5)$$ where $Q(z)$ is a polynomial and $k$ is a smallest $i>0$ such that $b_{i}\ne0$. i.e. if $P(z)=10z^{7}+6z^{5}+3z^{4}+4z^{3}+2z^{2}+1$, then $b_{0}=1$, $b_{k}=2$, $b_{1}=0$ and $$P(z)=1+2z^{2}+z^{3}(4+3z+6z^{2}+10z^{4})$$ Let $\omega\in\mathbb{C}$ be a $k$-th root from number $-\frac{b_{0}}{b_{k}}$, i.e. $\omega^{k}=-\frac{b_{0}}{b_{k}}$.
>Because $Q(z)$ is a polynomial there is some real number $t$ such that $$t|Q(t\omega)|\to0,\quad t\to0$$ From this we have that $t|\omega^{k+1}Q(t\omega)|\to0$, when $t\to0$. That is, exists some real number $t_{0}$, $0<t_{0}<1$ such that $$t_{0}|\omega^{k+1}Q(t_{0}\omega)|<|b_{0}|\quad(6)$$ So by $(5)$, we obtain $$\begin{align}P(t_{0}\omega)&=b_{0}+b_{k}(t_{0}\omega)^{k}+(t_{0}\omega)^{k+1}Q(t_{0}\omega)\\ &= b_{0}+b_{k}\left(t_{0}^{k}\left(-\frac{b_{0}}{b_{k}}\right)\right)+(t_{0}\omega)^{k+1}Q(t_{0}\omega)\\ &= b_{0}(1-t_{0}^{k})+(t_{0}\omega)^{k+1}Q(t_{0}\omega) \end{align}$$ 
>Therefore $$\begin{align}|P(t_{0}\omega)&\le(1-t_{0}^{k})|b_{0}|+t_{0}^{k+1}|\omega^{k+1}Q(t_{0}\omega)| \\ &<(1-t_{0}^{k})|b_{0}|+t_{0}^{k}|b_{0}|,\quad\text{by (6)}\\ &=|b_{0}|\\ &=|P(0)|&(7) \end{align}$$ But $(7)$ contradicts $(4)$. Thus supposition that $b_{0}\ne0$ is false, i.e. $P(0)=0$, as required.

***
#### Keywords
- [[Polynomial]],
- [[Complex plane]],
- [[Absolute value]],
- [[Set]],
- [[Open and closed subsets]],
- [[Bounded set]],
- [[Compact set]],
- [[Continuous mapping]],
- [[Supremum and infinum]]
- [[Function(mapping)]],
- [[Primitive root]],
- [[Real line]],
#### Possibly related
- [[Greatest element, upper bound and maximal element of a partially ordered set]]
***
#### Sources: