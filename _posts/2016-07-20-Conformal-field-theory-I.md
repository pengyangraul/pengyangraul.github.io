---
layout: post
title: "Conformal Field Theory I -- V. Gurarie"
date: 2016-07-20
category: Boulder School 2016
---

2D QFT with conformal symmetry. The partition function
\[
  Z =\int \mathcal{D} \varphi e^{-S}.
\]

## Conformal transformations
Given some tranformational law $x'^{\mu} = f^{\mu}(x)$,
\[
  \frac{dx^{\mu} dy^\mu}{\sqrt{dx^\alpha dx^\alpha} \sqrt{dy^\alpha dy^\alpha}}
  = 
  \frac{dx'^{\mu} dy'^\mu}{\sqrt{dx'^\alpha dx'^\alpha} \sqrt{dy'^\alpha dy'^\alpha}}.
\]
In terms of metric, $g_{\mu \nu}=\delta_{\mu\nu}$, then $g'\_{\mu \nu} = e^{\varphi(x')\delta_{\mu \nu}}$.

Type of transformations in $d$ dim:
- $x'^\mu = x^\mu + a^\mu$ \(translations, $d$ parameters\) 
- rotations $d(d-1)/2$ parameters
- scale transformations, $1$ parameters
- special conformal transformations, $d$ parameters

In 2 dim, it is better to use complex coordinate: $x+it = z$, $x-it = \bar{z}$. 
$x^2 + t^2 = z\bar{z}$. the metric tensor  $$ g = \left(
\begin{matrix}
  0 & 1/2 \\
  1/2 & 0
\end{matrix}\right) $$ and 
$$ g^{-1} = \left( \begin{matrix}
  0 & 2 \\
  2 & 0
\end{matrix}\right).$$
Then $z \bar{z}=g_{\mu\nu}z^\mu z^\nu$, with $z^{\mu} = (z,\bar{z})$. 
Introduce transformations $z = f(z')$ and $\bar{z}  = f^{\*}(\bar{z}')$,
\[ g'\_{z\bar{z}} = g_{z \bar{z}} \frac{\partial f}{\partial z'} \frac{\partial f^\*}{\partial \bar{z}'}. \]

## Consider inifinitesimal transformation (diffeomorphism)
$z' = z + \epsilon(z)$ and $\epsilon(z) = \sum_{n=0}^\infty \alpha_n z^{n}$,

- $z' = z+\alpha_0$
- $z' = z+\alpha_1 z$
- $z' = z+ \alpha_2 z^2$

Thses three gives  transformations
\[ z' = \frac{az + b}{cz + d}. \]

If a QFT is invariant under $x'^\mu = x^\mu + \epsilon^\mu(x)$,
then we have the conservation current $j_\mu = T_{\mu \nu} \epsilon^\nu$. 
1. Transl. $\epsilon^\nu = a^{\nu}$,  $\to$
$\partial^{\mu} j_\mu = \partial^\mu T_{\mu\nu}a^{\nu} = 0$.
2. Rot. $T_{\mu \nu} = T_{\nu \mu}$. 
3. $\epsilon^\nu\  = x^{\nu} \lambda$
$\to$ $\partial^\mu j_\mu = \partial^\mu (T_{\mu \nu} x^\nu) = 0 = T_{\mu}^{\mu}$ (Traceless).
4. $\partial^\mu j_\mu = \partial^\mu(T_{\mu\nu} \epsilon^\nu) = T_{\mu \nu} \partial^{\mu} \epsilon^\nu = T_{\mu\nu}
(\partial^\mu\epsilon^\nu + \partial^\nu\epsilon^\mu) \equiv T_{\mu \nu}.$

Correlation functions $\avg{A(z_1,\bar{z}_1) B(z_2,\bar{z}_2),\cdots}$.
\[A(z,\bar{z}) = A'(z',\bar{z}') \left(\frac{\partial z'}{\partial z}\right)^{h} \left(\frac{\partial \bar{z}'}{\partial
\bar{z}}\right)^{\bar{h}}, \]
where $h$ and $\bar{h}$ are called conformal dimensions.
The function transformed in this form are called primary fields.

Introduce diffeomorphism, $z' = z + \epsilon(z)$, we have
\[\delta A  = A(z,\bar{z})  - A'(z,\bar{z}) = \epsilon \partial_{z} A + \partial \epsilon h A. \]

Call $\avg{A(z,\bar{z}), B(w,\bar{w})} = G(z,\bar{z}; w,\bar{w})$.
1. $\epsilon = const$, we have $\delta G = \partial_{z} G + \partial_{w} G = 0$, we have
$G = G(z-w)$.
2. choose $\epsilon \sim z$, $\delta G = z \partial_z G + h_{A} G + w\partial_wG +h_{B}G = 0 $, 
we have \[ G = \frac{C}{ (z-w)^{h_A + h_B}}.\]
3. $\epsilon \sim z^{2}$, $\Rightarrow$ 
$G = 0$ unless $h_A = h_B$. 

Thus, we have
\[ G = \frac{C}{ (z-w)^{2 h_A}(\bar{z}-\bar{w})^{2 \bar{h}_A}}. \]

- Three point correlation: 
\[\avg{A(z_1) B(z_2) C(z_3)} =\frac{^C}{(z_1 - z_2)^{h_A + h_B - h_C} (z_2 - z_3)^{h_B + h_C - h_A}(z_3 - z_1)^{h_C +
h_A - h_B}}. \]

- Four point correlation function
\[ \avg{A(z_1) B(z_2) C(z_3) D(z_4)} = \frac{1}{(z_1 - z_3)^{2h_A} (z_2 - z_4)^{2 h_B}}F(x),\]
where 
\[ x = \frac{(z_1 - z_2 )(z_3 - z_4)}{(z_1 - z_4)(z_2 - z_3)}.\]
and $F(x)$ is called the Conformal block.

For general four point correlation functions, we have
\[\frac{1}{z_{13}^{2h_A} z_{24}^{2h_b} \bar{z}\_{13}^{2\bar{h}\_{A}} \bar{z}\_{24}^{2\bar{h}\_B}}   \sum_{ij} C_{ij}
F_{i}(x) F^\*_j(\bar{x}). \]

## Energy - stress tensor $T_{\mu \nu}$
Traceless condition: $T_{z \bar{z}} = 0$. 
Then we only have nonzero $T_{zz}$ and $T_{\bar{z} \bar{z}}$. 
$\Rightarrow$ 
$\partial T_{\bar{z} z} + \bar{\partial} T_{zz} =  \bar{\partial} T_{zz} = 0$.
We thus have
$T(z) = T_{zz} (z)$ and $\bar{T}(\bar{z}) = T_{\bar{z} \bar{z}}(\bar{z}) $.

## Radial quantization
Radial is time and angular is space. 
Define charge $Q = \oint dz \epsilon(z) T(\epsilon)$.
$\Rightarrow$ $$[Q,A] = \epsilon \partial A + h \partial \epsilon A.$$

\[\oint_{\abs{z} = \abs{w} + 0} dz \epsilon(z) T(z) A(w) - \oint_{\abs{z} = \abs{w} - 0} dz \epsilon(z) T(z) A(w)
  =\oint_{z = w + \rho e^{i \varphi}} \epsilon(z) T(z) A(w) dz 
\]

Thus we have the OPE
\[T(z) A(w) = \frac{h_A A(w)}{ (z - w)^2} + \frac{A'(w)}{z-w} + \cdots,\]
by applying Laurent expansion 
\[T(z) = \sum_{w = -\infty}^{w = \infty} L_n z^{-n-2}, \]
$T(z) A(0)$ $\Rightarrow$ $L_n A = 0$ for $n>0$; $L_0 A = h_A A$; $L_{-n} A \neq 0$ for $n>0$; $L_{-1} A = A'$. 

## Virasoro Algebra
Transformation laws of 
$\delta T(z) = \epsilon(z) T'(z) + 2\epsilon'(z) T(z) \epsilon'''(z) c/24$, where $c$ is called the central charge.
And
\[T(z) T(w) = \frac{c/2}{ (z - w)^4} + \frac{2 T(w)}{(z-w)^2} + \frac{T'(w)}{z-w} \cdots.\]
$L_0 T = 2T$, $L_{-1} = T'$, $L_2 T = c/2$. 
Computing commutators:
$$ [L_n,L_m] = (n-m)L_{n+m} + \frac{c}{12}(n^2 -n)\delta_{n+m,0}.$$






















