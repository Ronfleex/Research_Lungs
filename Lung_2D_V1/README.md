
### Lung_2D_V1

The code is in C++ via FreeFEM++.

## Introduction

The lung has a complex geometric structure. In this code, we find the mesh of the first level lung. To this we have added the Navier-Stokes code so that we can observe the flow in the lung while working on the boundary conditions.

For the boundary conditions, we are working with different types of edge, each with its own label:

- Label 0: Output 0 or input (the mouth)
- Label 1: Output number 1
- Label 2: Output number 2
- Label 20: all lateral edges 

![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/cb670805-e468-47b1-8a82-a470d0b1fa22)

## Utilisation

To make the code work, several variables can be changed, such as the Reynolds number, the time step and the boundary conditions. To view the animation, upload the files "Sol_Cavite2D_Reynolds=**Reynolds_number**_0.vtu to Paraview.

## Résultats 
https://github.com/Ronfleex/Research_Lungs/assets/129523736/d92193a0-70b6-42a4-85c1-84148d34d7c0
