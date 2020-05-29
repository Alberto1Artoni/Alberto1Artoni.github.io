---
format: page
title: Master Thesis
---


Here's the project I've followed during my [Master Thesis](https://alberto1artoni.github.io/assets/pdf/Tesi/TesiStile.pdf).

## PolyDG

The purpose of my thesis was to develop a 3D library able to solve the
Poisson problem on polyhedral meshes, exploiting a Polyhedral Discontinuos Galerkin (PolyDG) method.
Many applications are posed
on complicated geometries and the process of mesh generation is very
expensive. The PolyDG method supports very general meshes and allow the number of faces of each element to be arbitrarily large. Moreover,
some applications require high degree of accuracy, and again the
PolyDG method is naturally suited to accommodate high order accuracy.
In the thesis work I developed a new library, coded in Matlab and in
Fortran, that implements the PolyDG methods in three dimensions and
on arbitrary grids. A vast set of numerical tests validates the theoretical 
results and shows the performances of the developed libraries.

<p align="center">
  <img width="300" height="300" src="https://alberto1artoni.github.io/assets/pdf/Tesi/Immagini/Dominio.png">
</p>

### Matlab Library

Exploits sub-tessellation techniques. 

<p align="center">
  <img width="700" height="800" src="https://alberto1artoni.github.io/assets/pdf/Tesi/Immagini/SottoTassellazione.png">
</p>
### Fortran Library

Exploits a quadrature free method: for the moment it is able to deal only with polynomial doundary data and source. More research is on going, but the preliminares are promising.

####### Currently the software is private.
