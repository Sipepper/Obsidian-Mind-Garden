---
Last time checked: 2024-03-03
Complete: true
aliases:
---
# Compact set
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>A subset $B$ of topological space $(X,\tau)$ is said to be *compact* if for from every open covering we can extract a finite subcovering, i.e. if 
>$$B\subset\bigcup_{\alpha\in A}O_{\alpha}\quad O_{\alpha}\in\tau\;\forall\alpha\in A$$
>then there exists $\alpha_{1},\dots,\alpha_{n}\in A$ such that 
>$$B\subset O_{\alpha_{1}}\cup\dots\cup O_{\alpha_{n}}$$
>for some $n$.^[[[Fabio Silva Botelho - Functional Analysis and Applied Optimization in Banach Spaces.pdf#page=27|Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.9]]]

>[!example]+ 
>Let $(X,\tau)=\mathbb{R}$ and $A=(0,\infty)$, then $A$ is not compact.^[[[Sidney A. Morris - Topology without tears.pdf#page=176|Sidney A. Morris - "Topology without tears" p.176]]]
>
>>[!proof]+
>>For each positive integer $i$, let $O_{i}$ be the open interval $(0,i)$. Then, clearly, $A\subseteq \bigcup_{i=1}^{\infty}O_{i}$. But there do *not* exist $i_{1},i_{2},\dots,i_{n}$ such that 
>>$$A\subseteq(0,i_{1})\cup(0,i_{2})\cup\dots\cup(0,i_{n})$$
>>Therefore $A$ is not compact.

>[!example]+
>Let $(X,\tau)$ be a topological space and $A=\set{x_{1},x_{2},\dots,x_{n}}$ be an arbitrary finite subset of $X$. Then $A$ is compact.^[[[Sidney A. Morris - Topology without tears.pdf#page=176|Sidney A. Morris - "Topology without tears" p.176]]]
>
>>[!proof]+
>>Let $O_{i}$, $i\in I$ be any family of open sets such that $A\subseteq\bigcup_{i\in I}O_{i}$. Then for any $x_{j}\in A$ there exists $O_{i_{j}}$ such that $x_{j}\in O_{i_{j}}$. Therefore $A\subseteq O_{i_{1}}\cup O_{i_{2}}\cup\dots\cup O_{i_{n}}$. So $A$ is compact.

>[!example]+
>A subset $A$ of a discrete space $(X,\tau)$ is compact if and only if it is finite.^[[[Sidney A. Morris - Topology without tears.pdf#page=176|Sidney A. Morris - "Topology without tears" p.176]]]
>
>>[!proof]+
>>If $A$ is finite then by example above we know that $A$ is compact.
>>
>>Conversely, let $A$ be compact.  Then the family of singleton sets $O_{x}=\set{x}$, $x\in A$ is such that each $O_{x}$ is open and $A\subseteq\bigcup_{x\in A}O_{x}$. As $A$ is compact, there exist $O_{x_{1}},O_{x_{2}},\dots,O_{x_{n}}$ such that $A\subseteq O_{x_{1}}\cup O_{x_{2}}\cup\dots\cup O_{x_{n}}$; that is, $A\subseteq\set{x_{1},\dots,x_{n}}$. Hence $A$ is a finite set.
***
#### Keywords
- [[Set]],
- [[Topological space]],
- [[Open and closed subsets]],
- [[Covering of a set]],
- [[Cardinality of a set]],
- [[Real line]],
- [[Interval]],
- [[Set of integers]],
- [[Discrete topology]],
#### Possibly related
- 
***
#### Sources: