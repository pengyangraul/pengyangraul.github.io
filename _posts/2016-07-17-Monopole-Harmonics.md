---
layout: post
title: "Monopole Harmonics"
date: 2016-07-17
---

These notes are adapted from this [paper][ref1].

[ref1]: http://www.airitilibrary.com/Publication/alDetailedMesh?docid=05779073-200008-201210230016-201210230016-773-782 "Fung, Ming-Kong. "Spherical harmonics and monopole harmonics." Chinese Journal of Physics 38.4 (2000): 773-782."

# Spherical Harmonics

Consider a system of a single particle: $L=\frac{1}{2}m\dot{\boldsymbol{r}}^{2} \Rightarrow H=\frac{\boldsymbol{p}^{2}}{2m},\quad\boldsymbol{p}=m\dot{\boldsymbol{r}}$. We have the canonical commutation relation: $[r^{i},p^{j}]=i\delta_{ij}$.
The angular momentum operator is written as $\boldsymbol{L}=\boldsymbol{r}\times\boldsymbol{p},\quad[L^{i},L^{j}]=i\epsilon_{ijk}L^{k}$, 
and the angular part of the Hamiltonian can be written as 
\[
  H_{ang}=\boldsymbol{L}^{2}.
\]
Introduce Schwinger boson $a_{\zeta}^{\dagger}=(a_{+}^{\dagger},a_{-}^{\dagger})$ and $a_{\zeta}=(a_{+},a_{-})$, such that
\begin{equation}
[a_{\zeta},a_{\zeta'}]=0=[a_{\zeta}^{\dagger},a_{\zeta'}^{\dagger}],\quad[a_{\zeta,}a_{\zeta'}^{\dagger}]=\delta_{\zeta\zeta'}.
\nonumber
\end{equation} 
The number of spins and the resultant angular momentum are given by 

\begin{align} 
  n &= \sum_{\zeta} a_{\zeta}^\dagger a_{\zeta} = n_+ + n_-, \nonumber \\
  \v{L} &=  \sum_{\xi,\xi'}  a_{\xi}^{\dagger} \bra{\xi}\frac{1}{2}\sigma\ket{\xi'} a_{\xi'}. \nonumber
\end{align}

