### Lung_2D_V1_Respiratory_Tract

Le code est en C++ via FreeFEM++.

## Introduction

Le poumon a une structure géométrique complexe. Dans ce code, on retrouve le maillage du poumon du premier niveau. On a ajouter à cela le code de Navier-Stokes afin de pouvoir observer l'écoulement dans le poumon tout en travaillant sur les conditions aux limites.

Pour les conditions aux limites, nous travaillons avec types de bords différents avec chacun leur propre labels :

- Label 0 : Sortie 0 ou entrée (la bouche)
- Label 1 : Sortie numéro 1
- Label 2 : Sortie numéro 2
- Label 20 : tout les bords latérals 

![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/cb670805-e468-47b1-8a82-a470d0b1fa22)

## Utilisation

Pour faire fonctionner le code, plusieurs variables sont changeables comme le nombre de Reynolds, le pas de temps, les conditions aux limites. Pour visualiser l'animation, il faut téléverser les fichiers "Sol_Cavite2D_Reynolds=**Nombre_de_Reynolds**_0.vtu sur Paraview.

## Résultats 

https://github.com/Ronfleex/Research_Lungs/assets/129523736/003abf5c-7c8b-49a2-ae0a-13610e49466c


