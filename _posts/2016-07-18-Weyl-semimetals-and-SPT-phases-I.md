---
layout: post
title: "Weyl semimetals & SPT phases I -- Vishwanath"
date: 2016-07-18
category: Boulder School 2016
---

# Reference

- Beyond Band Insulators arxiv: 1301:0330
- Topological Semimetals & Interacting Symmetry Protected Topological Phase

# Plan  
- Energy gap + Free fermions \(From Andreas previous\)
- Close energy gap \(Topo. Properties survive? Translational symm.\); Weyl semimetals
  * Background
  * Weyl semimetals & Fermi arc surface states
  * Magnetic field --> case study \(Theory + Expts.\)

# Background

## Accidental Degeneracies
## Dirac & Weyl Equations
Dirac:
\begin{equation}
  i\partial_t \psi = \vec{\alpha}\dot (-i)\vec{\nabla} \psi + m\beta \psi
\end{equation}
Weyl: $m=0$. Massless fermion, odd spatial dimension. 
$\beta = \mathbb{I} \otimes \tau^{x}$, $\vec{\alpha} = \vec{\sigma} \otimes \tau^z$.
$\mathbb{I} \otimes \tau^z = i\alpha_1 \alpha_2 \alpha_3$.
\(That's why we need odd spatial dimension!\)
$\tau^z \psi _{\pm} = \pm \psi_{\pm}$ since $[\tau^z,H]=0$. 
We have
\begin{equation}
  H_{\pm} = \pm \vec{\sigma} \cdot (-i \vec{\nabla}),
\end{equation}
which is $\pm$ chirality of Weyl fermions. 

## Topological Band Invariants, ``C''
- Berry connection: \[A_{\alpha}(k) = -i \bra{u(k)} \frac{\partial}{\partial k_{\alpha}}\ket{u(k)}.\] 
- Berry curvature:
\[ F_{\alpha\beta} = \frac{\partial}{\partial k_{\alpha}}A_{\beta} - \frac{\partial}{\partial k_{\beta}}A_{\alpha}. \]
- Chern number: \[ \int \frac{dk^2}{2\pi} F(k) = C \]

# Weyl Semimetals
$H(k_x, k_y, k_z)$ nondegenerate bands, $T^2 = -1$, $(TI)^2 = -1$.
Break either $T$ or $I$. 
Let $k_{0}$ be the degenerate point in $k$ space. We analyze $H(k_0 + \delta k)$. 
Choose $H(k_0) = 0$, we simply expand the Hamiltonian
\begin{equation}
  H(k_0 + \delta k) = f_0(k+\delta k) + \vec{f}(k_0 +\delta k) \cdot \vec{\sigma},
\end{equation}
where
\begin{equation}
  f_{\mu} (k_0 + \delta k) = \vec{\delta k} \cdot (\vec{\nabla}f_{\mu}(k_0)) = \vec{v_{\mu}} \cdot \vec{\delta k}.
\end{equation}

Simple limit:
- $v_0 = 0$, $v_{a}^{i} = \delta_{ai} v$, 
\[H(k_0 + \delta k) = v \vec{\delta k} \cdot \vec{\sigma}.\]

Break $T$, preserve $I$
\begin{equation}
  H(k) = t\left( 2+\gamma - \cos(k_x) - \cos(k_y) - \cos(k_z) \right) \tau^z
  + t'\sin(k_x) \tau^x + t''\sin(k_y) \tau^y  
\end{equation}
where $\gamma\in (-1,1)$ to have a Weyl semimetal. 








