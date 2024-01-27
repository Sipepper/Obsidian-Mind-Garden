---
Last time checked: 2024-01-26
Complete: false
aliases:
---
# Category
***
###### tags: #Algebra/Category_theory 
***
>[!dsn]+ Definition
>A pair $\mathcal{A}=(\operatorname{Ob} A,\operatorname{Mor}A)$ is said to be the *category*, if for all $A,B\in\operatorname{Ob}A$ and $f:A\to B\in\operatorname{Mor}A$ the following conditions holds
>1. $f:A\to B$, $g:B\to C$ imply that $\exists g\circ f:A\to C$
>2. For all $A$ there exists $\operatorname{id}_{A}:A\to A$ such that $\forall f:A\to B$ and $\forall h:C\to A$
>   $$f\circ\operatorname{id}_{A}=f\qquad \operatorname{id}_{A}\circ h=h$$
>3. If $f:A\to B$, $g:B\to C$ and $h:C\to D$, then
>   $$(h\circ g)\circ f=h\circ(g\circ f)$$
>
>$\operatorname{Ob}A$ is a class of objects, and $\operatorname{Mor}A$ is a class of morphisms (arrows) between objects.^[[Lectures at KAU - Yevgen Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!example]+ 
>Let $\operatorname{Ob}A$ is a class of groups and $\operatorname{Mor}A$ the set of all group homomorphisms, then $(\operatorname{Ob}A,\operatorname{Mor}A)$ forms a category, namely *category of Groups* denoted as $\textbf{Grp}$.
>>[!proof]+
>>
***
#### Keywords
- [[Set]],
- [[Function(mapping)]],
- [[Group]],
- [[Homomorphism]]
#### Possibly related
- 
***
#### Sources: