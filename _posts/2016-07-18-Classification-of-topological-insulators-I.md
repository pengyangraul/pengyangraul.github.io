---
layout: post
title: "Classification of topological insulators I --A. Ludwig"
date: 2016-07-18
category: Boulder School 2016
---

References :arxiv 1512.08882, Phys. scr

# Classification of topological insulators and superconductors

- Intrinsic topological order: (eg. FQHE)
  * ground state degeneracy
  * anyons
- SPT phases
  * unique ground state
  * ground states cannont be deformed into direct product keeping symmetries
  * Eg. (2+1)D (p+ip) SC $\to$  $G=\mathbb{Z}_2$ fermion parity
- Topological insulators and superconductors for non-interacting fermions are the simplest SPTs
- Complete classfication
- Simplest + most fundamental classification scheme: systems with 
no symmetries that are unitarily realized on single-particle Hilbert space required to predict SPT.
- unitarily realized
  * translational
  * crystal (lattice)
  * SU(2) spin rotations
- Exhaustive classification: framework for all possible Hamiltonians (Ten-fold way)
- unitarily realized symmetry 
- block diagonalize the $H$ $\to$ 10 possible tyes of block Hamiltonians

# second quantized Hamiltoinan
\begin{equation}
  H = \sum_{A,B} \psi_{A}^{\dagger} H_{AB} \psi_{B},
\end{equation}
where $A,B$ are lattice labels from $1$ to $N$. There may also be spins labeled by $\sigma$s. We are interested in the thermodynamic limit. 
The above equation can also be written as a matrix, with Hamiltonian matrix $H$. 

## Unitarily realized symmetries

- $\exists$ group $G_{0}$, $N\times N$ unitary representation $u$  \($u_g, g \in G_0$\), s.t. $u^\dagger H u = H$.  
- For 2nd quantized operators, $u\psi_{A}u^\dagger=\sum_{B} \left(u^\dagger\right)\_{AB}\psi_{B}$, 
  $u \psi_{A}^{\dagger} u^\dagger = \sum_{B} \psi_{B}^{\dagger} u_{BA}$.
- N-dim single-particle hilbert spaces $\nu$ (spanned by $\ket{A} = \psi_{A}^{\dagger} \ket{0}$)
decomposes into 
\begin{equation}
  \nu = \bigoplus_{\lambda}^{\lambda = \mathrm{certerin\  irreps}} \nu_{\lambda}.
\end{equation}
In each $\nu_{\lambda}$ can choose basis fo the form
\[\ket{v^{\lambda}}\_{\alpha} \otimes \ket{w^{\lambda}}\_{k},\]
$k=1,\dots,d_{\lambda}=$ dim of $\lambda$. $G_{0}$ only act on $\ket{w}$, and  $H$ only act on $\ket{v}$. 

### Question:
Fix $G_{0}$, consider all $H$ commuting with all symmetry operations in $G_{0}$ unitarily realized. 
- As we run through these $H$s, what sets do the blockes $H^{\lambda}$ run through ? 

### Answer: 
Resulting set of block Hamiltonians $H^{\lambda}$ is independent of $G_{0}$ and the representation. 

### Fact (remarkable)
Only 10 possible such seets of matrices $H^{\lambda}$. 
Complete set of corresponding time-evolutionary operators:
\[ u^{\lambda}(t) = \exp (it H^{\lambda})  \]

### Why useful?
Problem of listing all possible Hamiltonians $\to$ finite problem. 

### What is behind the result ?
Symmetry in QM : unitary or antiunitary operator
Each blocks now can only depend on anitunitary symmetry.
Only a few anti-unitary symmetyr modulo unitary operators.

### Time reversal
In 2nd quant. $J$, 
\[ J\psi_{A}J^{-1} = \sum_{B} (u_{T})^{\dagger}\_{AB} \psi_{B}, \]
\[ J\psi_{B}^{\dagger}J^{-1} = \sum_{B}  \psi_{B}^{\dagger} (u_{T})\_{BA}, \]
where $J$ is anti-unitary operator, and $u_{T}$ is a unitary matrix. 
2nd quant. $H$ is invariant iff
\begin{equation}
  JHJ^{-1} = H  
\end{equation}
check equavalent to 1st quantized Hamiltonian $H$
\begin{equation}
  u_{T} H^{\*} u_{T}^{\dagger} = H .
\label{eq:1}
\end{equation}

Convenient $T := J\|_{1st\ quant.}$. Eq.(\ref{eq:1}) can be written as
\begin{equation}
  T H T^{-1} = H, \quad T = u_T K, \quad K^2 =1, \quad KHK^{-1} = H^{*} . 
\end{equation}

### Square of $J$ :
$J^2 = $ some unitary operator $U$ (fermion parity), corresponding to unitary matrix $u$. It can be shown that
\begin{equation}
  u = u_{T} u_{T}^{\*}.
\end{equation}
Follows from $J^2 H J^{-2} = J (J H J^{-1} J^{-1}) = H$, we have
$(u_T u_{T}^{\*})H = H (u_{T}u_{T}^{*})$, then $u_{T}u_{T}^{\*} = e^{i\gamma}\mathbb{I}$ by Schurs Lemma.  

Note that $u_{T} u_T^\* u_T = (u_T u_T^\*)u_T = u_T(u_T^\* u_T) = e^{i\gamma}u_T = u_T e^{-i\gamma}$, 
we have  $e^{i\gamma} = \pm 1$. Hence, $T^2 = \pm 1$. 

### Conclusion
3 ways Hamiltonian can respond to time-reversal. 

- H is not TR invariant
- $T^2 = 1$
- $T^2 = -1$ $J^2 \psi_A J^{-2} = - \psi_{A}$,  $J^2 \psi_A^\dagger J^{-2} = - \psi_{A}^\dagger$, $J^{2} = (-)^{Q}$, 
where  $Q = \sum_{A} \psi_{A}^\dagger  \psi_{A}$.  That's why it is called Fermion number parity operator. 











