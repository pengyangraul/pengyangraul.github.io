---
layout: post
title: "Classification of topological insulators III --A. Ludwig"
date: 2016-07-20
category: Boulder School 2016
---

### Comment on Superconductors
- BdG Hamiltonian $\to$ automatic $\mathcal{C}$-symmetry
- $\psi^T$ $\to$ $\chi^T = (\psi,\psi^{\dagger})^T$.
- \[ \mathcal{H}\_{BdG} =\frac{1}{2} \sum_{A,B} \chi_A H_{AB} \chi_B \]
- $\chi = \tau_1 (\chi^\dagger)^T$ $\Rightarrow$ $(\chi^\dagger)^T = \tau_1 \chi$ $\Rightarrow$ $\chi^\dagger = \chi^T \tau_1$
- \[ H = \frac{1}{2} \chi^\dagger H \chi = \frac{1}{2} \tau_1 H \tau_1 (\chi^\dagger)^T = \frac{1}{2} \chi^\dagger
(-\tau_1 H \tau_1 )^T \chi + \Tr (\tau_1 H \tau_1)\]
where the 2nd term vanishes. Thus, we have \[\tau_1 H^T \tau_1 = \tau_1 H^\* \tau_1 = -H .\]
The matrix $u_c = \tau_1$ in this situation. 

## Ten-Fold Way

### Classification

- Naively, 3 ways for $T$ and 3 ways for $C$. Almost true, but not !
- If $C= 0 = T$, then there are still two possibility for $S$: 
  * $S = 0$
  * $S = 1$
  * Then we have 10 ways.

We write $U(t) = \exp(itH))$. 

## Examples

### Class A 
When $T = C = S = 0$, then $U$ is an unitary matrix

### Class AI 
$T=1$, $C=0$, $S=0$ ($T^2=1$)

- $\exists$ basis s.t. $H$ is real and symmetric. 
Take an arbitrary Hermitian matrix, and we decompose it into symmetric and antisymmetric pieces:
\[ H = \frac{1}{2} (H + H^T) + \frac{1}{2}(H - H^T) = H_s + H_a\]
- Remeber $e^{itH} \in U(N)$, $e^{itH_a} \in O(N)$, $H_s = H-H_a$ $\Rightarrow$ $e^{itH_s} \in U(N)/O(N)$. 

## Class - topology
- Anderson localization (boundary approach)
- Bulk topology : K-theory
- Quantum Anomalies

### Basic ideas of topological band theory (Translation symmetry)

- $H(\vec{k}) \ket{u_a(\vec{k})} = E_{a}(\vec{k}) \ket{u_a(\vec{k})}$, where $\vec{k} \in T^d$. 
- Spectral flattening : $H(\vec{k}) \to Q(\vec{k})$, $Q(\vec{k}) = U(\vec{k}) \Lambda U(\vec{k})^{\dagger}$. 
- For $U(\vec{k}) = u_{0}(\vec{k}) = \diag(U_m(\vec{k}), U_n(\vec{k}))$. $U_0 \Lambda U_0^\dagger$, where
$\Lambda = \diag(\mathbb{I}_{n}, \mathbb{I}_m)$. 
- Thus $U(\vec{k}) \in U(n+m)/\left( U(m)\times U(n)\right) = G_{m,m+n}(\mathbb{C})$ (Grasmannian).
This is the classifying space. 
- $Q: BZ \to G_{m,m+n}(\mathbb{C}), \vec{k} \to Q(\vec{k})$.  (Assume spherical BZ)
- Characterized by 
\[
  \pi_d \left(U(m+n)/U(m)\times U(n) \right). 
\]
For $d = 2$, 
- \[
  \pi_2 \left(U(m+n)/U(m)\times U(n) \right) = \mathbb{Z}. 
\]
This classifies the 2D QH system. 

### Try to repeat for other symm. class
- K theory
- Intuition about $Q(\vec{k})$

Classifying: 
\begin{align}
  \pi(\bar{T}^{d}, R_{q}) = \pi_d(R_q-d) \oplus \bigoplus_{s=0}^{d-1}
  C_{d}^{s} \pi_0(R_{q-s})
\end{align}
where the first term classifies the strong topological phase, and the second term classifies the weak topological
phases. 

## Classify by Anderson localization

- Boundaries of toplogical insulators or SC must avoid Anderson localization. 
- Classifying top. ins. and sc in the bulk $\Leftrightarrow$ 
classifying $\bar{d} = d-1$ dim Anderson localization at the boundary.  

## Anderson localization problems at length scales $\gg$ mean free path: NLSM
- NLSM: Stat mech classical Ferromagnetic $\vec{S} \in S^{2}$. 
- Anderson localization $\vec{S} \in$ Cartan spaces. 
- NLSM $\bar{d}$ 
\[ 
  S = \frac{1}{g} \int d^d r \sum_{\mu=1}^{\var{d}}\Tr\left( \partial_\mu \Phi(r) \partial_\mu \Phi(r) \right), + S_{\mathrm{top}}\left( \Phi(r)\right)
\]
where $\Phi(r) \in G/H =$ Cartan space.
Check whether $S_{top}$ exists or not to identify the classification.
















