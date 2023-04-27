# Asymptotic inequalities and equivalence relations for functions
***
###### tags: #Fundamental_math_objects 
***
#### Approximately equivalent functions
>[!dsn]+ Direct strict note
>Let $X$ be a subset of $\mathbb{R}$. Given two functions $f,g:X\to\mathbb{R}$, we say that *the order of the function $f$ is at most the order of the function $g$* denoted as $f\precsim g$, if there exist real numbers $a,b,c,d,e>0$ and $x_{0}$ such that for all $x\in X,x\ge x_{0}$, we have: $bx+c\in X$ and 
>$$f(x)\le ag(bx+c)+dx+e$$
>If $f\precsim g$ and $g\precsim f$ then we say that $f$ and $g$ are *approximately equivalent*, denoted as $f\approx g$.^[Cornelia Drutu, Michael Kapovich - "Geometric group theory" c.2]

>$\approx$ is an equivalence relations
>>[!proof]+
>>$f\precsim f$, as $f(x)\le ag(bx+c)+dx+e$ for $a=1$, $b=1$, $c=1$, $d=0$, $e=0$, that is $f(x)\le f(x)$.
>>
>>Suppose that $f\approx g$, then $f\precsim g$ and $g\precsim f$ thus symmetric property holds.
>>
>>Let $f\approx g$ and $g\approx h$, then
>>$$f(x)\le a_{1}g(b_{1}x+c_{1})+d_{1}x+e_{1}\le a_{1}(a_{2}h(b_{2}(b_{1}x+c_1)+c_{2}))$$
>>$$\begin{align}f(x)&\le a_{1}g(b_{1}x+c_{1})+d_{1}x+e_{1}\\ &\le a_{1}(a_{2}h(b_{2}(b_{1}x+c_{1})+c_{2})+d_{2}x+e_{2})+d_{1}x+e_{1}\\ &\le a_{1}a_{2} h(b_{2}b_{1}x+b_{2}c_{1}+с_{2})+(a_{1}d_{2}+d_{1})x+a_{1}e_{2}+e_{1}\\ &\le k_{a_{1},a_{2}}h(k_{b_{1},b_{2}}x+k_{b_{2},c_{1},c_{2}})+k_{a_{1},d_{2},d_{1}}x+k_{a_{1},e_{2},e_{1}} \end{align}$$
>>that is $f\precsim g$ and $g\precsim h$ imply $f\precsim h$, the reversed implication can be verified in a same way.

#### Approximately equal functions
>[!dsn]+ Direct strict note
>Given two functions $f,g:X\to\mathbb{R}$, where $X\subset\mathbb{R}$, we can introduct the *asymptotic inequality* between functions $f$ and $g$, denoted as $f\preceq g$, if there exist $a,b>0$ and $x_{0}\in\mathbb{R}$ such that for all $x\in X$,$x\ge x_{0}$, we have: $bx\in X$ and
>$$f(x)\le ag(bx)$$
>If $f\preceq g$ and $g\preceq f$ then we write $f\asymp g$ and say that $f$ and $g$ are *asymptotically equal*.^[Cornelia Drutu, Muchael Kapovich - "Geometric group theory" c.2]

>$\asymp$ is an equivalence relations
>>[!proof]+
>>

>Supose that $x\preceq f$, $x\preceq g$. Then $f\approx g$ if and only if $f\asymp g$.
>>[!proof]+
>>

>[!example]+
>
***
#### Keywords
- [[Set]],
- [[Function(mapping)]],
- [[Real line]],
- [[Equivalence relation]]
#### Possibly related
- 
***
#### Sources: