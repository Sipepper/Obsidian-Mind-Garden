# Euclidean algorithm
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Theorem
>Let $a,b\in\mathbb{Z}$, $b>0$, then
>$$\begin{align}a&=bq_{0}+r_{0}&0\le r_{0}<b\\ b&=bq_{1}+r_{1}&0\le r_{1}<r_{0}\\ r_{0}&=r_{1}q_{2}+r_{2}&0\le r_{2}<r_{1}\\&\qquad\vdots&\vdots\qquad\\ r_{n-2}&=r_{n-1}q_{n}+r_{n}&0\le r_{n}<r_{n-1}\\ r_{n-1}&=r_{n}q_{n+1}+0\end{align}$$
>And $gcd(a,b)=r_{n}$.

>[!proof]+
>Let $a,b,q,r\in\mathbb{Z}$, $b\ne0$. Let $a=bq+r$, then $gcd(a,b)=gcd(b,r)$, as
>$$(c|a)\land(c|b)\Rightarrow a=cs,\quad b=ct$$
>and
>$$cs=ctq+r,\quad r=c(s-tq)\Rightarrow c|r\Rightarrow (c|b)\land(c|r)$$
>Thus
>$$\begin{align}gcd(a,b)&=gcd(b,r_{0})\\gcd(b,r_{0})&=gcd(r_{0},r_{1})\\ \vdots\qquad&\quad\qquad\vdots\\ gcd(r_{n-2},r_{n-1})&=gcd(r_{n-1},r_{n})\\ gcd(r_{n-1},r_{n})&=gcd(r_{n},0)=r_{n}=gcd(a,b) \end{align}$$

>[!example]+ 
>$a=30$, $b=42$,
>$$30=0\cdot 42+30\qquad 30=30-0\cdot 42$$
>$$42=30\cdot 1+12\qquad12=42-30\cdot 1$$
>$$30=12\cdot 2+6\qquad 6=30-12\cdot 2$$
>$$12=6\cdot 2+0$$
>So $6=gcd(30,42)$, and 
>$$6=30-(42-30\cdot 1)\cdot2=-2\cdot 42+3\cdot 30$$
***
#### Keywords
- [[Set of integers]],
- [[Division with remainder]],
- [[Greatest common divisor]],
- [[Logical operators]],
- [[Divisibility]]
#### Possibly related
- 
***
#### Sources: