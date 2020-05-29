---
format: page
title: Master Thesis
---


Here's the project I've followed during my Master Thesis. 
<a href="assets/pdf/Tesi/TesiStile.pdf" class="image fit"></a>

## PolyDG

The purpose of this work is to develop a 3D library able to solve the
Poisson problem on polyhedral meshes, exploiting a Polyhedral Discontinuos Galerkin (PolyDG) method.
Many applications are posed
on complicated geometries and the process of mesh generation is very
expensive. The PolyDG method supports very general meshes and al
low the number of faces of each element to be arbitrarily large. Moreover,
some applications require high degree of accuracy, and again the
PolyDG method is naturally suited to accommodate high order accuracy.
In this work we develop a new library, coded in Matlab and in
Fortran, that implements the PolyDG methods in three dimensions and
on arbitrary grids. A vast set of numerical tests validates the theoretical 
results and shows the performances of the developed libraries.


### Matlab Library

Exploits sub-tessellation techniques.

### Fortran Library

Exploits the quadrature free method.

###### Currently the software is private.
