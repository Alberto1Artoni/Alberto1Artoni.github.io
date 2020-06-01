---
title: Ising Model
---


### Dinamica dei sistemi complessi

Dinamica dei sistemi complessi is a nice introductive course about networks. It covers the main statistics and the main properties of the network, with some attention to dynamics (for instace it treats the SIR model).
Course evaluation can be integrated with a project.

The [project](https://alberto1artoni.github.io/assets/pdf/Ising/ArtoniAlbertoRConIsing.pdf) I've choose was basically to obtain all the results presented in paper [1].
The code has been implemented using Mathematica and mainly the related library iGraph. The project has been discussed on 12/04/2019.

## Ising Model
First, let us introduce the Ising Model. 
The Ising model can be seen as a formal system with some specific update rules. 

- consider an adjacency matrix **A**.
- consider a proper $\mathcal{H}$ (energy) functional
- update with a probability ~ *P*(H)
- loop several times

|:--------------------:|:--------------------:|
|![](https://alberto1artoni.github.io/assets/pdf/Ising/IsingMag.gif)| ![](https://alberto1artoni.github.io/assets/pdf/Ising/IsingNoMag.gif)|
| T &lt; T<sub>c</sub> | T &gt; T<sub>c</sub> |

In the left we have magnetization: the lattix change all his colors. In the right, due to high temperature, we don't have magnetization.
The Ising model was firtly proposed for 1D lattix; it has then been extended to 2D results. It is generally unclear what happens (theoretically) on different topologies. The paper aims to propose some "experimental" (simulation) results.

## Ising Model on fully uncorrelated networks

Fully uncorrelated networks have community. We reach local "magnetization" in each comunity. Increasing the temperature we see that the stronger community are no more magnetized, while the weaker show magnetization.

Visual example for T=10.
<p align="center">  <img width="500" height="175" src="https://alberto1artoni.github.io/assets/pdf/Ising/IsingUncT10.gif"> </p> 

Evolution of the dynamics:
<p align="center"> <img width="400" height="500" src="https://alberto1artoni.github.io/assets/pdf/Ising/NonZeroTemp.png"> </p>

From the paper we have:

![](https://alberto1artoni.github.io/assets/pdf/Ising/Corr.png)

For T=10 the results are qualitatevly the same.

[1] Jorg, Valleriani and Reinhard, Sequences of phase transitions in ising models on correlated networks.


<p> <span style="color:grey"> Images shown are GIFs - with no loop.
 Some browser-related issues are known: please open the page with Chrome </span></p>

