# Extension of a homomorphism of a subgroup of abelian group to divisible abelian group
***
###### tags: #Group_Theory 
***
>[!dsn]+ Direct strict note
>Let $H$ be a subgroup of an abelian group $G$. If $\phi$ is any homomorphism of $H$ into a divisible abelian group $D$, then $\phi$ can be extended to a homomorphism $\Phi$ of $G$ into $D$.^[Sidney A. Morris - "Topology without tears" p.530]

>[!proof]+
>By [[Zorn's lemma]], it suffices to show that if $x\notin H$, $\phi$ can be extended to the group $H_{0}=\{x^{n}h:h\in H,n\in\mathbb{Z}\}$.
>Case $(i)$. Assume $x^{n}\notin H$, $n\in\mathbb{N}$. Then define $\Phi(x^{n}h)=\phi(h)$, for all $n\in\mathbb{Z}$. 
>Case $(ii)$. Let $k\ge2$ be the *least* positive integer $n$ such that $x^{n}\in H$. So $\phi(x^{k})=d\in D$. As $D$ is divisible, there is a $z\in D$ such that $z^{k}=d$. Define $\Phi(x^{n}h)=\phi(h)z^{n}$, for all $n\in\mathbb{Z}$. Clearly $\Phi$ is well-defined, a homomorphism and extends $\phi$ on $H$.

>[!example]+ 
>
***
#### Keywords
- [[Group]],
- [[Abelian group]],
- [[Homomorphism]],
- [[Divisible abelian group]],
- [[Restriction and extension of a mapping]],
- [[Function(mapping)]]
#### Possibly related
- [[Transfinite induction]]
***
#### Sources: