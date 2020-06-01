---
title: Ising Model
---


### Dinamica dei sistemi complessi


The [project](https://alberto1artoni.github.io/assets/pdf/Ising/ArtoniAlbertoRConIsing.pdf) was basically to obtain all the results presented in paper [1].
The code has been implemented using Mathematica and mainly the related library iGraph. The project has been discussed on 12/04/2019.

## Ising Model
Ising Model basics and history.
Explain the model:


![](https://alberto1artoni.github.io/assets/pdf/Ising/IsingMag.gif)| ![](https://alberto1artoni.github.io/assets/pdf/Ising/IsingNoMag.gif)
 T &lt; T<sub>c</sub> | T &gt; T<sub>c</sub>

In the left we have magnetization: the lattix change all his colors. In the right, due to high temperature, we don't have magnetization.
The Ising model was firtly proposed for 1D lattix; it has then been extended to 2D results. It is generally unclear what happens (theoretically) on different topologies. The paper aims to propose some "experimental" (simulation) results.

## Ising Model on fully uncorrelated networks

Fully uncorrelated networks have community. We reach local "magnetization" in each comunity. Increasing the temperature we see that the stronger community are still magnetize, while the weaker show no magnetization.

Visual example for T=10.
![](https://alberto1artoni.github.io/assets/pdf/Ising/IsingUncT10.gif)

State after a large number of iteration, varying the temperature:
![](https://alberto1artoni.github.io/assets/pdf/Ising/NonZeroTemp.png)

[1]  ̈Jorg, Valleriani and Reinhard, Sequences of phase transitions in ising models on correlatedi networks.
<p> <span style="color:grey"> Images shown are GIFs - with no loop.
 Some browser-related issues are known: please open the page with Chrome </span></p>

