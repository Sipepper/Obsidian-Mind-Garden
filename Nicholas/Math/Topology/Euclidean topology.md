# Euclidean topology
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>A subset $S$ of $\mathbb{R}$ is said to be open in the *euclidean topology on $\mathbb{R}$* if it has the following property:
>- For each $x\in S$ there exist $a,b\in\mathbb{R}$, with $a<b$, such that $x\in(a,b)\subseteq S$.^[Sidney A. Morris - "Topology without tears" p.51]

>The "euclidean topology" $\tau$ is a topology.
>>[!proof]
>>Firstly, let $x\in\mathbb{R}$. If we put $a=x-1$ and $b=x+1$ then $x\in(a,b)\subseteq\mathbb{R}$, that is $\mathbb{R}\in\tau$. Secondly $\emptyset\in\tau$.
>>
>>Let $\set{A_{j}:j\in J}$, for some index set $J$, be a family of members of $\tau$. Then we have to show that $\bigcup_{j\in J}A_{j}\in\tau$. Let $x\in\bigcup_{j\in J}A_{j}\in\tau$, then $x\in A_{k}$, for some $k\in J$. As $A_{k}\in\tau$, there exist $a,b\in\mathbb{R}$ with $a<b$ such that $x\in(a,b)\subseteq A_{k}$. As $k\in J$, $A_{k}\subseteq\bigcup_{j\in J}A_{j}$ and so $x\in(a,b)\subseteq\bigcup_{j\in J}A_{j}$, therefore it belongs to $\tau$.
>>
>>Finally, let $A_{1}$ and  $A_{2}$ be in $\tau$. Let $y\in A_{1}\cap A_{2}$. Then $y\in A_{1}$. As $A_{1}\in\tau$, then there is $(a,b)$ such that $y\in(a,b)\subseteq A_{1}$. Also $y\in A_{2}\in\tau$. So there exist $(c,d)$ such that $y\in(c,d)\subseteq A_{2}$. Let $e=\max\{a,c\}$ and $f=\min\{b,d\}$, then $y\in(e,f)$. As $(e,f)\subseteq(a,b)\subseteq A_{1}$ and $(e,f)\subseteq(c,d)\subseteq A_{2}$, then $y\in(e,f)\subseteq A_{1}\cap A_{2}$. Hence $A_{1}\cap A_{2}\in\tau$.
>>Thus $\tau$ is indeed a topology. 
***
#### Keywords
- [[Topological space]],
- [[Set]],
- [[Interval]],
- [[Open and closed subsets]],
#### Possibly related
- 
***
#### Sources:

# 2.2.10.О топологии на конечномерных евклидовых пространствах.
Обобщая [[Topology basis|понятие базы топологии]] мы понимаем как можно построить топологию на $\mathbb{R}^n$ 
$$\mathbb{R}^n=\{(x_1,x_2,\dots,x_n)|x_i\in\mathbb{R},i=1,\dots,n\}$$ для каждого натурального числа $n>2$. Пусть тогда $\mathfrak{B}$ - набор всех подмножеств вида $$\{(x_1,x_2,\dots,x_n)\in\mathbb{R}^n|a_i<x_i<b_{i},i=1,\dots,n\}$$ со сторонами которые паралельны осям. Тогда набор $\mathfrak{B}$ будет базисом для *евклидовой топологии* на $\mathbb{R}^n$.

#### Линки
[[Euclidean topology]],
[[Topology basis]],
[[Open and closed subsets]],
[[Topological space]]
#### Тэги 
 #Topology