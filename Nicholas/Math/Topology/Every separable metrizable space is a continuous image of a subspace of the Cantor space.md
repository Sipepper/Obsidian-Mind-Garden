---
Last time checked: 2024-03-05
Complete: false
aliases:
---
# Every separable metrizable space is a continuous image of a subspace of the Cantor space
***
###### tags: #Topology 
***
>[!dsn]+ Theorem
>Every separable metrizable space $(X,\tau_{1})$ is a continuous image of a subspace of the Cantor Space $(G,\tau)$. Further, if $(X,\tau_{1})$ is compact, then the subspace can be chosen to be closed in $(G,\tau)$.^[[[Sidney A. Morris - Topology without tears.pdf#page=248|Sidney A. Morris - "Topology without tears" p.248]]]

>[!proof]+
>Let $\phi$ be the continuous mapping of $(G,\tau)$ onto $I^{\infty}$ shown to exist in the proof of [[Hilbert's cube#Compactness]]. By [[separability and metrizability criterion using Hilbert cube]], $(X,\tau_{1})$ is homeomorphic to a subspace $(Y,\tau_{2})$ of $I^{\infty}$. Let the homeomorphism of $(Y,\tau_{2})$ onto $(X,\tau_{1})$ be $\Theta$. Let $Z=\psi^{-1}(Y)$ and $\tau_{3}$ be the subspace topology on $Z$. Then $\Theta\circ\psi$ is a continuous mapping of $(Z,\tau_{3})$ onto $(X,\tau_{1})$. So $(X,\tau_{1})$ is a continuous image of the subspace $(Z,\tau_{3})$ of $(G,\tau)$.
>
>Further if $(X,\tau_{1})$ is compact, then $(Y,\tau_{2})$ is compact and hence closed in $I^{\infty}$. So $Z=\psi^{-1}(Y)$ is a closed subset of $(G,\tau)$, as required.

>[!example]+ 
>
***
#### Keywords
- [[Separable space]],
- [[Metrizable space]],
- [[Continuous mapping]],
- [[Kernel and image of a mapping]],
- [[Subspace topology]],
- [[Cantor space]],
- [[Compact set]],
- [[Open and closed subsets]],
- [[Hilbert's cube]]
- [[Homeomorphism]],
- [[Preimage]],
- [[Function(mapping)]],
#### Possibly related
- 
***
#### Sources: