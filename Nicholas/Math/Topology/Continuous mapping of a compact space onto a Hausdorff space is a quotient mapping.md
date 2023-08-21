# Continuous mapping of a compact space onto a Hausdorff space is a quotient mapping
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $f$ be a continuous mapping of a compact space $(X,\tau)$ onto a hausdorff space $(Y,\tau_{1})$. Then $f$ is a quotient mapping.^[Sidney A. Morris - "Topology without tears" p.339] 

>[!proof]+
>Let $A$ be a subset of $Y$. If $f^{-1}(A)$ is closed in $(X,\tau)$, then by [[Closed subset of compact space is compact]] it is compact. As $f$ is continuous, by [[Continuous image of compact space is compact]], $f(f^{-1}(A))$ is compact subspace of the Hausdorff space $(Y,\tau_{1})$, and therefore by [[Compact subset of Hausdorff space is closed]] is closed in $(Y,\tau_{1})$. As $f$ is surjective, $f(f^{-1}(A))=A$, and we have that $A$ is closed.
>
>Conversely, if $A$ is closed in $(Y,\tau_{1})$, then by continuity of $f$, $f^{-1}(A)$ is closed in $(X,\tau)$.
>Hence $f$ is a quotient mapping.

>[!example]+ 
>
***
#### Keywords
- [[Continuous mapping]],
- [[Compact set]],
- [[Hausdorff space]],
- [[Quotient topology]],
- [[Set]],
- [[Preimage]],
- [[Open and closed subsets]],
#### Possibly related
- 
***
#### Sources: