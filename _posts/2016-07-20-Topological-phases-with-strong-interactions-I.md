---
layout: post
title: "Topological phases (SRE) with strong interactions I -- A. Vishwanath"
date: 2016-07-20
category: Boulder School 2016
---

- Integer quantum Hall + Interactions $\Rightarrow$ new phases $\mathbb{Z} \times \mathbb{Z}$ (Bosonic topological
phases \"cooper pairs\"). 
- 3D TI $\to$ Dirac cone gappless / gapped with symmetry breaking: 
Gapped symmetric surface $\to$ \"Pfaffian state\"
- Experiments ?  New insights into the $\nu = 1/2$ quantum Hall Composite Fermions.

## Phases of matter $N\to \infty$

### Phases without symmetry
Quantum Wegner model

### Example II & III
Majorana wire i & p+ip superconductor

- Short Range Entangled
  * Gapped bulk
  * \"bulk\" is simple , excitations conventional
  * Distinction: edge states. 
  * unique gound state on torus
  * $\gamma=0$ (topological entanglement entropy)
- Long Range Entangled (Toric code; FQHE)
  * Gapped bulk
  * Exotic bulk excitations
  * Gapped state degenerate on torus
  * $\gamma>0$ 

## Set of short range entangled phases ($G$)
- $G$ internal symmetry, e.g. $SU(2)\_{spin}$, $\mathbb{Z}\_2$ etc., not space group. 
- Set $\to$ Group + Abelian (also for free fermion, see the table)
  * Identity: trivial phase
  * Group Addition: composition of phases, adding interaction with all sorts of symmetry-allowed local terms.
  * Inverse element ?  $H(x,y,z)$ is phase $g$, $H(-x,y,z)$ is the inverse $-g$. 

### Example Boson/Spins & $G = SO(3)$; Ground state symm. 
 
- Haldane Model (spin-1 Heissenberg interaction) $\to$ SRE protected by $G$ (SPT). \($\mathrm{Y_2 Ba Ni O_5}$\)
- 1D $SO(3)$ $\to$ $\mathbb{Z}\_2$ classification 
- Restrict to $\pi$ rotations around $x,y,z$ direction
$g_x^2=g_y^2=g_z^2=1$, $g_x g_y = g_z$. 
$\mathbb{Z}\_2 \times \mathbb{Z}\_2 = G$. 
$\Rightarrow$ $\mathbb{Z}\_2$ SPT phases.

## Duality
- Describe phases in terms of symmetry defects. Some SPTs $\to$ achieve by condensing \"decorated\"
defects.
- Duality for $1+1D$ Ising $\to$ Domain Walls
\[ H = -J\left( \sum_{i} \sigma_i^z \sigma_{i+1}^{z} + \sum_{i} \sigma_i^{x}\right).\]
- $\mathbb{Z}\_2$ symmetry: \[ \tilde{g} = \prod_{i} \sigma_i^x .\]
This measures the $\mathbb{Z}\_2$ charge. $\tilde{g} H \tilde{g}^{-1} = H$.
\[\sigma^x \ket{0} = \ket{0}\]
\[\sigma^x \ket{1} = -\ket{1}.\]
Creating charge by $\sigma_i^z$ which will be the same as destructing.

- Phase diagram
* small $g$, ordered phase (condensation of $\mathbb{Z}\_2$ charges)

### Domain walls
Each domain wall cost energy $\Delta = 2J$. 
$\tilde{x}\_{i+1/2} = \sigma_{i}^z \sigma_{i+1}^z$ measures a domain wall
$\tilde{z}\_{i+1/2} = \prod_{j>i} \sigma_j^x $ creates a domain wall.

- Self-dual $g \to 1/g$
- SPT $\to$ $\mathbb{Z}\_2 \times \mathbb{Z}\_2 $
- Free fermion representation: $\chi = \sigma_i^z \tilde{\sigma}\_{i+1/2}^{z}$.
(Create a charge and domain wall bound together).
- \"Condense domain walls \" $\to$ disordered phase , restore $\mathbb{Z}\_2$. 
- One can also condense with another charge
$\avg{\tilde{\sigma}^z_i \mu^z_{i+1}} \neq 0$, where $mu^z$ is a different  $\mathbb{Z}\_2$ charge.
One can construct SPT Hamiltonian: 
\[H = -J\left(\sum_{i} \sigma_i^z \mu_{i+1}^x \sigma_{i+2}^z + \mu_{i}^z \sigma_{i+1}^{x} \mu_{i+2}^{z} \right). \]




