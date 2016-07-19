---
layout: post
title: "Classification of topological insulators II --A. Ludwig"
date: 2016-07-19
category: Boulder School 2016
---

## Charge-conjugation symmetry
In Fock space, operator $\mathcal{C}$
\[\mathcal{C} \psi_A \mathcal{C}^{-1} = \sum_{B} (u_c^{\*})\_{AB}^\dagger \psi_B^\dagger \]
\[\mathcal{C} \psi_A^\dagger \mathcal{C}^{-1} = \sum_{B}\psi_B  (u_c^{\*})\_{AB} \]
\[\mathcal{C} i \mathcal{C}^{-1} = i \]
where $u_c$ is an unitary matrix.

2nd quant., $\mathcal{H}$ is charge-conjugation invariant $\Leftrightarrow$ $\mathcal{C} \mathcal{H} \mathcal{C}^{-1}=\mathcal{H}$.
This is equivalent to the first quantized Hamiltonian $H$
\[  u_c \left( H - \frac{1}{2}\Tr(H) \right)^t u_c^\dagger = - \left( H - \frac{1}{2}\Tr(H) \right)\]
and
\[   u_c H^* u_c^\dagger =-H. \]

It is convenient to write $C = \mathcal{C} |_{1st \ quant. }$. 
We have $C H C^{-1} = -H$, where $C = u_c K$. 

### Square of C:
If  $\mathcal{C}^2 = \mathcal{u}$, then  $C^2 = u = u_c u_c^\*$.
And $[u,H] = 0$. 

As for time-reversal operator, we conclude that $u = u_c u_c^\* = \pm 1$, $C^2= \pm 1$. 

### Conclusion
There are 3 ways a Hamiltonian can respond to charge conjugation symmetry. 

- Not invariant
- $C^2 = 1$ 
- $C^2 = -1$ $\Rightarrow$ 
\[\mathcal{C}^2 \psi_A \mathcal{C}^{-2} = (-) \psi_{A}\]
\[\mathcal{C}^2 \psi_A^\dagger \mathcal{C}^{-2} = (-) \psi_{A}^\dagger\]
For 2nd quant. Hamiltonian, we have $\mathcal{C}^{2} = (-)^{Q}$, which is the Fermion parity operator.

The Fock space $\mathcal{F}$ is graded, meaning
\[
  \mathcal{F} = \bigoplus_{q=0}^{\infty} \mathcal{F}\_{q}.
\]
Then $\mathcal{C}: \mathcal{F}\_q \to \mathcal{F}\_{N-q}$. In particular, it maps $\mathcal{F}\_0$ to
$\mathcal{F}\_{N}$. 

## Chiral (Sublattice) Symmetry
Define
\[\mathcal{S} = \mathcal{T} \mathcal{C}.\]
we have 
\[\mathcal{S} \psi_A \mathcal{S}^{-1} = \sum_{B} (u_s^{\*})\_{AB}^\dagger \psi_B^\dagger \]
\[\mathcal{S} \psi_A^\dagger \mathcal{S}^{-1} = \sum_{B}\psi_B  (u_s^{\*})\_{AB} \]
\[\mathcal{S} i \mathcal{S}^{-1} = -i \]
where $u_s = u_T u_c^\*$.

2nd $\mathcal{H}$ is $\mathcal{S}-$invariant, we have
$\{u_s,H\}=0$ $\Rightarrow$ $\Tr H = 0$.

Introduce $S = \mathcal{S}|_{1st \  quant}$. We have 
$ S = T C $ $u_s = u_T u_c^\*$, and  $ [S,H] = 0. $

### Square of S
$S^2 H S^{-2} = H $. $S^2 = (u_s)^2 = e^{i\phi}\mathbb{I}$. 
We can always make a phase choice $u_T \to e^{i\phi_T} u_T$, $u_c \to e^{i\phi_c} u_c$,
s.t. $\phi = 0$, to make $S^2 = (u_s)^2 =1$, and $S^{\dagger} = S$.

If we define $\mathcal{S}' = \mathcal{C} \mathcal{T}$. Then we have
\begin{equation}
  \mathcal{S} = \epsilon_{C}\epsilon_{T} \mathcal{S}'
\end{equation}
where $\epsilon_C$ and $\epsilon_{T}$ are $\mathcal{C}$ and $\mathcal{T}$ square to ($\pm 1$).

We need to use the result that $u_{T}^t = \epsilon_T u_T$, and $u_{c}^t = \epsilon_c u_c$.

## Comment
Need to consider only one $T$ and one $C$ !



















