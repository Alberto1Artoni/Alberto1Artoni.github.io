---
title: APSC
format: page
---

### Advanced Programming for scientific computing

The course introduces to the scientific C++ standards. The final examination consists in a project carried out with the Math department professors.

Me and Elisabetta Chimisso carried out a project on fluid structure iteration (FSI) with contact. The main tasks were to add a second structure in an already well structured code and to take into account the contact. Contact was enforced with a penalization technique.
For me this project have been crucial in the years of the master degree: finally I've applied all my studies to something quite practical. I think this is the project I've enjoyed the most.

For the project we have made a [final report](https://alberto1artoni.github.io/assets/pdf/FSI/ArtoniChimisso_ContactProblemForCardiacValveMechanics.pdf), a presentation for the [programming part](https://alberto1artoni.github.io/assets/pdf/FSI/ArtoniChimissoPACS.pdf) and a presentation for the [numerical part]().

## Fluid Structure iteraction with applications to cardiac valves

The main goal of the project is to solve a contact problem involving two structures immersed
in a fluid. We discussed the theoretical and numerical formulation of the problem, mainly following the original paper [1]. Then we describe the contact algorithm that relies on a explicit penalty method.
The implementation conisted in two steps:
- add the second structure
- apply a contact search algorithm
In chapter three we present the results: first without any contact, then we test the goodness
of the contact search algorithm and finally we try to solve some problems.

### Two structures with no contact

A linear elastic law is imposed on the structures. On the top and bottom boundary Neumann boundary conditions are taken into account. On the left and right boundary null Dirichlet conditions are imposed. Both the structures are pintched towards the center and then released.
The images shows the evolution of the valve, without contact.

![](https://alberto1artoni.github.io/assets/pdf/FSI/gif/Valve.gif)


### Contact example

We tested a ball (with linear elastic constitutive law) falling in an ideal fluid. As you can see, the ball stops on the structure below: no change of topology happens, as expected.

![](https://alberto1artoni.github.io/assets/pdf/FSI/gif/Ball.gif)



[1] P. F. Antonietti, M. Verani, C. Vergara, and S. Zonca. Numerical solution of fluid-
structure interaction problems by means of a high order discontinuous galerkin method
on polygonal grids. 2018

###### Images shown are GIFs - with no loop. Some browser-related issues are known: please open the page with Chrome.
