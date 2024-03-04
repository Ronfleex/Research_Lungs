### Lung_2D_V2

Le code est en C++ via FreeFEM++.

## Introduction

Le poumon a une structure géométrique complexe. Dans ce code, on retrouve le maillage du poumon du second niveau. On a ajouter à cela le code de Navier-Stokes afin de pouvoir observer l'écoulement dans le poumon tout en travaillant sur les conditions aux limites.

Pour les conditions aux limites, nous travaillons avec types de bords différents avec chacun leur propre labels :

- Label 0 : Sortie 0 ou entrée (la bouche)
- Label 1 : Sortie numéro 1
- Label 2 : Sortie numéro 2
- Label 3 : Sortie numéro 3
- Label 4 : Sortie numéro 4 
- Label 20 : tout les bords latérals

![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/2e5982e2-0042-4e6b-9cd4-7116aafc21c4)


## Utilisation

Pour faire fonctionner le code, plusieurs variables sont changeables comme le nombre de Reynolds, le pas de temps, les conditions aux limites. Pour visualiser l'animation, il faut téléverser les fichiers "Sol_Cavite2D_Reynolds=**Nombre_de_Reynolds**_0.vtu sur Paraview.

## Résultats 

https://github.com/Ronfleex/Research_Lungs/assets/129523736/3c2ba6b1-b7bd-4536-8db4-920b90f9b4bb


