# Homeomorphism
***
###### tags: #Topology #Fundamental_math_objects 
***
>[!dsn] Direct Strict note
>Let $(X,\tau)$ and $(Y,\tau_{1})$ - be a topological spaces. Then they called a *homeomorphic to each other* if there exists a mapping $f:X\rightarrow Y$ such that following properties holds:
>1. $f$ - injective function, i.e. $f(x_1)=f(x_2)\Rightarrow x_1=x_2$
>2. $f$ - surjective function, i.e. $\forall y\in Y,\exists x\in X:f(x)=y$
>3. $\forall U\in\tau_{1}, f^-1(U)\in\tau$;
>4. $\forall V\in\tau, f(V)\in\tau_{1}$;
>>Mapping $f$ - is called a *homeomorphism* between $(X,\tau)$ and $(Y,\tau_{1})$. Denoted as $(X,\tau)\cong(Y,\tau_{1})$.^[Sidney A. Morris - "Topology without tears" c.96]

>[!example] 
>Let $(X,\tau)=[0,2]$ and $(Y,\tau_{1})=[0,1]\cup[2,3]$ then $[0,1]=[0,1]\cap Y\Rightarrow[0,1]$ is closed in $(Y,\tau_{1})$ и $[0,1]=(-1,1\frac{1}{2})\cap Y\Rightarrow[0,1]$ - is open in $(Y,\tau_{1})$. Therefore $Y$ - is not connected because it has $[0,1]$ as a clopen subset not equal to $\emptyset$ or whole space $Y$.
>Suppose that $(X,\tau)\cong(Y,\tau_{1})$. Then exists homeomorphism $f:(X,\tau)\rightarrow(Y,\tau_{1})$. Therefore preimage $f^{-1}([0,1])$ will be a clopen subset of $X$, from this we have that $X$ - is not a conneted space. We came to contradiction because $[0,2]=X$ is obviously a connected space. Therefore $(X,\tau)\ncong(Y,\tau_{1})$.

#### Homeomorphism criterion
>[!dsn]+ Direct strict note
>Let $(X,\tau)$ and $(Y,\tau')$ be topological spaces and $f$ a function from $X$ into $Y$. Then $f$ is homeomorphism if and only if
>- $f$ is continuous
>- $f$ is one-to-one and onto; that is, the inverse function $f^{-1}:Y\to X$ exists
>- $f^{-1}$ is continuous.^[Sidney A. Morris - "Topology without tears" p.115;]
***
#### Transitivity of a homeomorphism
>[!dsn]+ Direct strict note 
>Let $(X,\tau)$, $(Y,\tau_1)$ and $(Z,\tau_2)$ are topological spaces. If $(X,\tau)\cong(Y,\tau_1)$ and $(Y,\tau_1)\cong(Z,\tau_2)$, then $(X,\tau)\cong(Z,\tau_2)$.^[Sidney A. Morris - "Topology without tears" p.97]

>[!proof]+
>

#### Homeomorphism is an equivalence relation
>[!dsn]+ Direct strict note
>Let $(X,\tau)$, $(Y,\tau_{1})$ and $(Z,\tau_{2})$ be topological spaces, then
>1. $(X,\tau)\cong(X,\tau)$ (*reflexive*)
>2. $(X,\tau)\cong(Y,\tau_{1})$ implies $(Y,\tau_{1})\cong(X,\tau)$ (*Symmetric*)
>3. $(X,\tau)\cong(Y,\tau_{1})$ and $(Y,\tau_{1})\cong(Z,\tau_{2})$ implies $(X,\tau)\cong(Z,\tau_{2})$ (*Transitive*)
>
>i.e. homeomorphism is an *equivalence relation*.^[Sidney A. Morris - "Topology without tears" p.97]

>[!proof]+
>
***
#### Properties which invariant to a homeomorphism
1. $T_{0}$-space.
2. $T_{1}$-space.
3. $T_{2}$-space or Hausdorffness.
4. Regular space.
5. $T_{3}$-space.
6. Being second countable.
7. Separability.
8. Discrete space.
9. Indiscrete space.
10. Cofinite topology.
11. Countably-closed topology.
***
#### Keywords
- [[Topological space]],
- [[Function(mapping)]],
- [[Preimage]],
- [[Interval]],
- [[Connected topological space]],
- [[Open and closed subsets]],
- [[Continuous mapping]],
- [[Inverse function]],
- [[Equivalence relation]],
- [[T0 space]],
- [[T1 space]],
- [[Hausdorff space]],
- [[Regular and T3 space]],
- [[Second axiom of countability]],
- [[Separable space]],
- [[Discrete topology]],
- [[Indiscrete topology]],
- [[Cofinite topology]],
- [[Countably-closed topology]]
#### Possibly related
- 
***
#### Sources: