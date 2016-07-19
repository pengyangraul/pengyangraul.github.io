---
layout: post
title: "Many-body localization"
date: 2016-07-18
category: Boulder School 2016
---

# Outline
- What it is
- Exotic states protected by MBL
- Emergent integrability
- Outlook

### Traditionally 
Assume ergodicity, equilibration, loss of info about the initial condition.

### Isolated quantum many body system
\[ i\partial_t \rho = [H,\rho] \]
- Information accessible in local measurement on subregion A contained in $\rho_{A} = \Tr_{B} \rho $.
Does $\lim_{t\to \infty} \rho_A(t)$ look like a thermal density matrix ? 
If yes, equivalent to ergodicity. 

### Eigenstates thermalization hypothesis (ETH)
- Deutsch 91
- Everyc many body eigenstate in equilibrium fulfills
\[ \Tr \ket{\psi}\bra{\psi} \propto \exp(-\beta H_A), \]
$\beta$ depends the energy of the many body state $\ket{\psi}$. 


# Localization
Localization is known to happen in disordered quantum systems. 
## MBL 
- Dynamical phase of matter, robust to generic perturbations. 
- Non-ergoticity, does not equilibrate
- (FUNDAMENTAL) Preserve memory of inintial condition for  $\infty$ times. 

### Model
\begin{equation}
  H = \vec{S_{i}}\cdot\vec{S_{i+1}} + \lambda_i S_{i}^{z} 
\end{equation}
where $\lambda_{i}$ are random variables. 

- Def Full MBL: All eigenstates violate ETH. 

## Localization protected order[^1]
[^1] Huse, RN, et. al Sondhi; 2013
New form of order with no analog in equilibrium.
\begin{equation}
  H = J S_{i}^{z} + S_{i+1}^z +\lambda S_i^x + \epsilon S_{i}^x S_{i+1}^x
\end{equation}
- $\lambda \ll 1$, $\epsilon <<1$, cat states $\ket{\uparrow\uparrow\uparrow} \pm
\ket{\downarrow\downarrow\downarrow}$.
Diagonostic: correlation functions $\avg{S_i^{z}(t)S_i^z(0)}$, and $\lim_{\abs{i-j}\to \infty}\avg{S_i^z(0)S_j^z(0)}$
Adding disorer $\lambda \to \lambda_i$ , $J \to J_i$, localized Domain wall. 
New eigenstates are cat states, degenerate, $\delta E \propto \exp(-L/\xi)$. 
Symmetry breaking takes time $\exp(tL/\xi)$ to relax.

### Majorana Chain
Kitaev's model has Majorana edge modes in all eigenstates. 
Q: Is this stable ? Can bulk exicatation couple the two ends ? 
Avoid this either by eliminating bulk exicatation of ground state, or by localizing the bulk excitation on disorder.
Stablet Majoranas in highly excitated states. 

### FMBL $\Rightarrow$ emergent integrability
Facts: 
- No transport in MBL phase
- entanglement grows $\propto \log(t)$. 

Given an FMBL Hamiltonian $H(\{\sigma_{i}\})$, we can find a localized unitary transformation to new objects
\begin{equation}
  \tau_z^i = U(\sigma,\sigma\sigma,\sigma\sigma\sigma)  .
\end{equation}
This  $U$ is localized in real space with exponential tail.
\begin{equation}
  H = h_{i} \tau^z_i + J_{ij} \tau^z_i \tau^z_j + K_{ijk} \tau^z_i \tau^z_j \tau^z_k,
\end{equation}
where $J_{ij}$ and higher order coefficients fall off expoenetially $\sim \exp(-R/\xi)$, 
every $\avg{\tau_i^z}$ is independently a local integral of motion (LIOM). 
No transport, but there is dephasing. Spins precesses in mutual field. Two spins
entangle on time scales $t$ s.t $J_{eff} t \sim 1$, $J_{eff} \sim \exp(-R/\xi)$, 
$\exp(-R/\xi)t \sim 1 \Rightarrow R \sim \xi \ln(t) $. 

### Emergent integrability
- Model has extensive # LIOMs



