---
layout: post
title: "Monte Carlo Strategies for Spin Liquids I -- R. Melko"
date: 2016-07-22
category: Boulder School 2016
---

# Classical MC approaches $\to$ spin liquids

Two examples: 
- Spin ice 
- Surface codes $\Leftarrow$ Threshold calculation

## Monte Carlo
Observables \[\avg{O} = \frac{\sum_{x} O(x) e^{-\beta E_x}}{\sum_x e^{-\beta E_x}}\]
$\Rightarrow$ important sampling $\Rightarrow$ generating $x$ accordinglye to $W_{x}$.

### Metroplis algorithm 
- propose an update $x \to x'$
- compute the difference in energy $\Delta E= E'-E$
- $\Delta E\leq 0$, accept the proposal
- $\Delta E > 0$, $p = e^{-\beta \Delta E}$, accept only when $p>r$, with $r$ an random number. 

Conditions:
- detailed balance : $W_{x}P(x\to y) = W_y P(y\to x)$.
- ergodicity: any state can be generated from other state in finite steps $\to$ can't prove but important

### Example \"Square ice\" D.O.F. $\sigam^z = \pm 1$.
\[ H = \sum_{vertexs}Q_{v}^2, \quad Q_v \sum_{i\in v} \sigma_i^z.\]
This is like $(\nabla \cdot E)_{v} = 0$.
- Residual entropy: $S = N_{0} \log 3/2$ (Pauling estimate)
\[\Delta S = \int_{T_{low}}^{T_{high}} C/T dT\]

