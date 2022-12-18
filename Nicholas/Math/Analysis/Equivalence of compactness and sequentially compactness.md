# Equivalence of compactness and sequentially compactness
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>A subset $A$ of a metric space $(U,d)$ be a compact set if and only if it is a sequentially compact set.^[Botelho - Functional analysis and Applied Optimization in Banach Spaces с.15-18]

>[!proof]
>Suppose that $A$ is a compact set. From proposition [[Countably compact set#Relation to compactness|about countably compactness of a compact set]] we obtain that $A$ is countably compact. Let $\{u_{n}\}\subset A$ be some sequence. We get two cases 
>1. $\{u_{n}\}$ has infinite number of equal elements; i.e. $$u_{n_{1}}=u_{n_{2}}=\dots=u_{n_{k}}=\dots=u\in A$$ From which we see that theorem is trivial in that case.
>2. $\{u_{n}\}$ has infinite number of distinct elements. In that case, if $A$ is countably compact, then $\{u_{n}\}$ has a limit point which lay in $A$, it means that exist a convergent subsequence $\{u_{n_{k}}\}$ such that $$u_{n_{k}}\to u,\quad k\to\infty$$ 
>
>In both cases we can find a subsequence converging to some point $u\in A$. Which means that $A$ is sequentially compact.
>
>Converse, let $A$ be a sequentially compact set, and suppose that $\{G_{\alpha}:\alpha\in L\}$ is an open covering of $A$. For all $u\in A$ define a map $$\delta(u)=\sup\{r:B_{r}(u)\subset G_{\alpha},\alpha\in L\}$$ First let's show that $\delta(u)\ge0$,$\forall u\in A$. Fix some $u\in A$. Because $A\subset\bigcup_{\alpha\in L}G_{\alpha}$, there exists an $\alpha_{0}\in L$ such that $u\in G_{\alpha_{0}}$. By opennes of $G_{\alpha_{0}}$ there exist an $r_{0}>0$ such that $B_{r_{0}}(u)\subset G_{\alpha_{0}}$. Therefore $$\delta(u)\ge r_{0}>0$$ Now we define a $\delta_{0}$ as $$\delta_{0}=\inf\set{\delta(u):u\in A}$$ Then, there exist a sequence $\{u_{n}\}\subset A$ such that $$\delta(u_{n})\to\delta_{0},\quad n\to\infty$$ Because $A$ is sequentially compact, we can form a subsequence $\{u_{n_{k}}\}$ and choose element $u_{0}\in A$ such that $$\delta(u_{n_{k}})\to\delta_{0},\quad u_{n_{k}}\to u_{0}$$ When $k$ is approaching infinity. Then we can find some $K_{0}\in\mathbb{N}$ such that if $k>K_{0}$, then $$d(u_{n_{k}},u_{0})<\frac{\delta(u_{0})}{4}\quad(1)$$ We need to show that $$\delta(u_{n_{k}})\ge\frac{\delta(u_{0})}{4},\quad\text{if}\quad k>K_{0}$$ to do that we suppose that $$z\in B_{\frac{\delta(u_{0})}{4}}(u_{n_{k}}),\quad\forall k>K_{0}$$ Note that from $(1)$ we can obtain following $$u_{0}\in B_{\frac{\delta(u_{0})}{4}}(u_{n_{k}}),\quad\forall k>K_{0}$$ 
>Because $$\frac{\delta(u_{0})}{2}<\delta(u_{0})$$ there exists some $\alpha_{1}\in L$ such that $$B_{\frac{\delta(u_{0})}{2}}(u_{0})\subset G_{\alpha_{1}}$$
>Because $$d(u_{n_{k}},u_{0})<\frac{\delta(u_{0})}{4},\quad k>K_{0}$$ we get $$B_{\frac{\delta(u_{0})}{2}}(u_{0})\supset B_{\frac{\delta(u_{0})}{4}}(u_{n_{k}}),\quad k>K_{0}$$ such that $$\delta(u_{n_{k}})\ge\frac{\delta(u_{0})}{4},\quad\forall k>K_{0}$$
>Therefore $$\lim_{k\to\infty}\delta(u_{n_{k}})=\delta_{0}\ge\frac{\delta(u_{0})}{4}$$
>Now choose $\varepsilon>0$ such that $$\delta_{0}>\varepsilon>0$$
>By theorem [[Теорема о вполне-ограниченности через подпоследовательности]] it follows that $A$ is completely bounded set. For $\varepsilon$ chosen before we choose a $\varepsilon$-net which is contained in $A$ and denote it by $N$
>$$N=\set{v_{1},\dots,v_{n}}\subset A$$
>Because $\delta>\varepsilon$, there exists $$\alpha_{1},\dots,\alpha_{n}\in L$$ such that $$B_{\varepsilon}(v_{i})\subset G_{\alpha},\quad\forall i\in\set{1,\dots,n}$$ noting that $$\delta(v_{i})\ge\delta_{0}>\varepsilon>0,\quad\forall i\in\set{1,\dots,n}$$
>Because for $A$, $N$ is an $\varepsilon$-net we get $$u\in\bigcup_{i=1}^{n}B_{\varepsilon}(v_{i})\subset\bigcup_{i=1}^{n}G_{\alpha_{i}}$$
>By arbitrarity of $u\in U$ we obtain that $$A\subset\bigcup_{i=1}^{n}G_{\alpha_{i}}$$
>Therefore $$\set{G_{\alpha_{1}},\dots,G_{\alpha_{n}}}$$ is a finite subcoverring of $A$ from covering $$\set{G_{\alpha}:\alpha\in L}$$
>Thus $A$ is a compact set as required.

>[!example] 
>
***
#### Keywords
- [[Множество]],
- [[Metric space]],
- [[Компактное множество]],
- [[Последовательно компактное множество]],
- [[Покрытие множества]],
- [[Открытое и замкнутое множества]],
- [[Supremum and infinum]],
- [[Открытый шар]],
- [[Последовательность]],
- [[Epsilon-net]]
#### Possibly related
- 
***
#### Sources: