# Peano theorem
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>For each positive integer $n$, there exists a continuous mapping $\psi_{n}$ of $[0,1]$ onto the $n$-cube $I^{n}$.^[Sidney A. Morris - "Topology without tears" p.251]

>[!proof]+
>By [[Every compact metrizable space is a continous image of the Cantor space]], there exists a continuous mapping $\phi_{n}$ of the Cantor Space $(G,\tau)$ onto the $n$-cube $I^{n}$. As $(G,\tau)$ is obtained from $[0,1]$ by successively dropping out middle thirds, we extend $\phi_{n}$ to a continuous mapping $\psi_{n}:[0,1]\to I^{n}$ by defining $\psi_{n}$ to be linear on each omitted interval; that is, if $(a,b)$ is one of the open intervals comprising $[0,1]\setminus G$, then $\psi_{n}$ is defined on $(a,b)$ by
>$$\psi_{n}(\alpha a+(1-\alpha)b)=\alpha\psi_{n}(a)+(1-\alpha)\phi_{n}(b)\quad0\le\alpha\le1$$
>"verification that $\psi_{n}$ is continuous".

>[!example]+ 
>
***
#### Keywords
- [[Set of integers]],
- [[Continuous mapping]],
- [[Hilbert's cube]],
- [[Interval]],
- [[Cantor space]],
- [[Restriction and extension of a mapping]],
- [[Linear map]],
- [[Open and closed subsets]],
#### Possibly related
- 
***
#### Sources: