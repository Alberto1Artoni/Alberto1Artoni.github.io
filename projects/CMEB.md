---
format: page
title: CMEB
---

### Computational Modeling in Electronics and Biomathematics (CMEB)

The course is a numerical course that features the main modelling sources of non linearities and explains how to deal with them from a numerical point of view. The main applicative areas considered are electronics and biomathematics: huge comparisons are made, and surprisingly share lot of modelling techniques.

A [project](https://alberto1artoni.github.io/assets/pdf/CMEB/KMCPDEs.pdf) integrates the theoretical written exam. In this project I integrated my knowledge connected to the mechanical-statistical field with the PDE world. 

## Coupling a PDE Problems with the Kinetic Monte-Carlo

I've interfaced in the FEMOS 3D library both a Poisson and a thermal coupling with the Kinetic MonteCarlo approach.

Here is the structure of the proposed algorithm:
<p align="center">  <img width="400" height="700" src="https://alberto1artoni.github.io/assets/pdf/CMEB/SchemaSolutore.png"> </p> 
![]()

## Results

The imposed electric field (computed with the Poisson equation) moves the particles. The temperature (computed via heat equation) makes the particle vibrate.
On the right the Poisson's problem solution: as you can see there are areas in which the electric field is higher. This is due to the net unbalance of the charge.
Also, on the right we solve the thermal equation: solution is linear, having lower temperatures on the top and higher on the bottom. Particles moves accordingly.

<p align="center">  <img width="400" height="400" src="https://alberto1artoni.github.io/assets/pdf/CMEB/coupled.gif"> </p> 
 <p align="center"><img width="200" height="225" src="https://alberto1artoni.github.io/assets/pdf/CMEB/poissonCoup.png">   
<img width="200" height="225" src="https://alberto1artoni.github.io/assets/pdf/CMEB/thermalCoupl.png"> </p>

## Further developments

The project is a first step in more detailed investigation about the coupling between the particle world and the PDE world. This is one of the first attemps. From a practical point of view, devices like RRAM can be designed.


###### Images shown are GIFs - with no loop. Some browser-related issues are known: please open the page with Chrome.
