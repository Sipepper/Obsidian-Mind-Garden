---
Last time checked: 2023-10-12
complete: true
aliases:
---
# Congruent integers
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Definition
>Let $a,b,n\in\mathbb{Z}$, $n\ge0$. We say that $a$ *congruent* $b$ *modulo* $n$, if $n|(b-a)$. Denoted as
>$$a\equiv b\mod{n}$$

>We also can define congruence with $n<0$, but from definition it is clear that
>$$(a\equiv b\mod{n})\Leftrightarrow(a\equiv b\mod{(-n)})$$

>If $a\equiv b\mod{0}$ then $a=b$.

>Congruence of integers is an equivalence relation.
>>[!proof]+
>>1. $a\equiv a\mod{n}\Leftrightarrow n|(a-a)$, which is always true(the $a|0$)
>>2. Let $a\equiv b\mod{n}$, then $n|(b-a)$, so
>>   $$b-a=nk\Rightarrow a-b=-kn\Rightarrow n|(a-b)$$
>>3. Let $a\equiv b\mod{n}$ and $b\equiv c\mod{n}$, then
>>   $$b-a=nk\quad\text{and}\quad c-b=nl$$
>>   thus
>>   $$c-a=(c-b)+(b-a)=n(l+k)$$
>>   so $n|(c-a)$.

>[!example]+ 
>Let $a=4$ and $b=7$, then
>$$a\equiv b\mod{3}$$
>as $7-4=3$, and $3|3$.

***
#### Keywords
- [[Set of integers]],
- [[Divisibility]],
- [[Equivalence relation]]
#### Possibly related
- 
***
#### Sources: