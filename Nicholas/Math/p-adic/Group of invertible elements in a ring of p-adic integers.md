# Group of invertible elements in a ring of p-adic integers
***
###### tags: #p-adic #Algebra 
***
>[!dsn] Direct strict note
>The group $\mathbb{Z}_{p}^{\times}$ of invertible elements in the ring $\mathbb{Z}_{p}$ consists of the $p$-adic integers of order zero, namely
>$$\mathbb{Z}_{p}^{\times}=\left\{\sum\limits_{i\ge0}a_{i}p^{i}:a_{0}\ne0\right\}$$
>.^[Alain M. Robert - "A course in p-adic analysis"]

>[!proof]
>If a $p$-adic integer $a$ is invertible, so must be its reduction $\varepsilon(a)$ in $\mathbb{F}_{p}$. This proves the inclusion $\mathbb{Z}_{p}^{\times}\subset\left\{\sum_{i\ge0}a_{i}p^{i}:a_{0}\ne0\right\}$. Conversely, we have to show that any $p$-adic integer $a$ of order $v(a)=0$ is invertible in this field. Choose $0<b_{0}<p$ with $a_{0}b_{0}\equiv1\mod{p}$ and write $a_{0}b_{0}=1+kp$. Hence, if we write $a=a_{0}+p\alpha$, then
>$$a\cdot b_{0}=1+kp+p\alpha b_{0}=1+p\kappa$$
>for some $p$-adic integer $\kappa$. It suffices to show that the $p$-adic integer $1+\kappa p$ is invertible, since we can then write
>$$a\cdot b_{0}(1+\kappa p)^{-1}=1,\quad a^{-1}=b_{0}(1+\kappa p)^{-1}$$
>In other words, it is enough to treat the case $a_{0}=1$, $a=1+\kappa p$. Let us observe that we can take
>$$(1+\kappa p)^{-1}=1-\kappa p+(\kappa p)^{2}-\dots=1+c_{1}p+c_{2}p^{2}+\dots$$
>with integers $c_{i}=\set{0,1,\dots,p-1}$. This possibility is assured if we apply the rules for carries suitably.
***
#### Keywords
- [[Group]],
- [[Group of invertible elements in a ring]],
- [[Ring of p-adic integers]],
- [[p-adic order]],
- [[Reduction modulo p]],
- [[Finite field]],
#### Possibly related
- 
***
#### Sources: 