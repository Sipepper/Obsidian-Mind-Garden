---
Last time checked: 2024-01-26
Complete: true
aliases:
---
# Quotient ring
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Proposition
>Let $R$ be a ring and $I$ be an ideal. Then the set $R/I$ of all ring cosets has a ring structure with respect to operations
>$$\begin{align}(a+I)+(b+I)&:=(a+b)+I\\ (a+I)\cdot(b+I)&:=(a\cdot b)+I \end{align}$$
>Then $(R/I,+,\cdot)$ is called the *quotient ring*.^[[Lectures at KAU - Yevgen Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!proof]+
>Associativity of addition:
>$$\begin{align}((a+I)+(b+I))+(c+I)&=((a+b)+I)+(c+I)\\ &=(((a+b)+c)+I)\\ &=((a+(b+c))+I)\\ &=(a+I)+((b+c)+I)\\ &=(a+I)+((b+I)+(c+I)) \end{align}$$
>Existence of neutral element:
>$$a+I+0_{R}+I=(a+0_{R})+I=(0_{R}+a)+I=a+I$$
>Commutativity of addition:
>$$\begin{align}(a+I)+(b+I)&=(a+b)+I\\ &=(b+a)+I\\ &=(b+I)+(a+I) \end{align}$$
>Associativity of multiplication:
>$$\begin{align}((a+I)(b+I))(c+I)&=(ab+I)(c+I)\\ &=(ab)c+I\\ &=a(bc)+I\\ &=(a+I)(bc+I)\\ &=(a+I)((b+I)(c+I)) \end{align}$$
>Existence of identity:
>$$\begin{align}(a+I)(1_{R}+I)=a\cdot1_{R}+I=1_{R}\cdot a+I=a+I \end{align}$$
>Distributivity
>$$\begin{align}(a+I)(b+I+c+I)&=(a+I)((b+c)+I)\\ &=a(b+c)+I\\ &=(ab+ac)+I\\ &=ab+I+ac+I\\ &=(a+I)(b+I)+(a+I)(b+I) \end{align}$$

>[!example]+ 
>Let $R=\mathbb{Z}$ and $I=n\mathbb{Z}$ then $\mathbb{Z}/n\mathbb{Z}$ is a familiar ring defined in [[modular arithmetic]].

>If $R$ is a commutative ring, $I$ is an ideal. Then $R/I$ is also a commutative ring.
>>[!proof]+
>>Indeed, let $a,b\in R$. We have that
>>$$(a+I)(b+I)=ab+I=ba+I=(b+I)(a+I)$$

>We can associate a map $\pi:R\to R/I$ which maps $a$ to $a+I$. It's a surjective homomorphism with $\ker\pi= I$.
>>[!proof]+
>>$\pi$ is surjective by definition(as $I\subset R$). Then
>>$$\pi(a)+\pi(b)=a+I+b+I=(a+b)+I=\pi(a+b)$$
>>and
>>$$\pi(0_{R})=0_{R}+I=0_{R/I}$$
>>thus $\pi$ is a homomorphism and $\ker\pi=I$.
***
#### Keywords
- [[Ring]],
- [[Ideal]],
- [[Ring coset]],
- [[Law of composition]],
- [[Associative property]],
- [[Commutative property]],
- [[Set of integers]],
- [[Function(mapping)]],
- [[Homomorphism]],
- [[Kernel and image of a mapping]]
#### Possibly related
- [[Quotient set]]
***
#### Sources: