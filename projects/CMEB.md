---
format: page
title: PDE-KMC
---

### Computational

The course is about

## Coupling a PDE Problems with the Kinetic Monte-Carlo

I've interfaced in the FEMOS 3D library both a Poisson and a thermal coupling with the Kinetic MonteCarlo approach.

Qui metto l'immagine in tikz di che succede

Finally, several configurations have been explored.

## Results

The imposed electric field (computed with the Poisson equation) moves the particles. The temperature (computed via heat equation) makes the particle vibrate.
On the right the Poisson's problem solution: as you can see there are areas in which the electric field is higher. This is due to the net unbalance of the charge.
Also, on the right we solve the thermal equation: solution is linear, having lower temperatures on the top and higher on the bottom. Particles moves accordingly.

:-------------------------:|:-------------------------:
  <img width="500" height="450" src="https://alberto1artoni.github.io/assets/pdf/CMEB/coupled.gif"> |   <img width="250" height="225" src="https://alberto1artoni.github.io/assets/pdf/CMEB/poissonCoup.png">   <img width="250" height="225" src="https://alberto1artoni.github.io/assets/pdf/CMEB/thermalCoupl.png">

## Further developments

The project is a first step in more detailed investigation about the coupling between the particle world and the PDE world. This is one of the first attemps. From a practical point of view, devices like RRAM can be designed.


###### Images shown are GIFs - with no loop. Some browser-related issues are known: please open the page with Chrome.
