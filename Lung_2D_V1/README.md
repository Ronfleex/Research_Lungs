
### Lung_2D_V1

Le code est en C++ via FreeFEM++.

## Introduction

Le poumon a une structure géométrique complexe. Dans ce code, on retrouve le maillage du poumon du premier niveau. On a ajouter à cela le code de Navier-Stokes afin de pouvoir observer l'écoulement dans le poumon tout en travaillant sur les conditions aux limites.

Pour les conditions aux limites, nous travaillons avec types de bords différents avec chacun leur propre labels :

- Label 0 : Sortie 0 ou entrée (la bouche)
- Label 1 : Sortie numéro 1
- Label 2 : Sortie numéro 2
- Label 20 : tout les bords latérals 

![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/84706fa0-6752-4d1b-aae5-425e7156ea9b)

## Utilisation

Pour faire fonctionner le code, plusieurs variables sont changeables comme le nombre de Reynolds, le pas de temps, les conditions aux limites. Pour visualiser l'animation, il faut téléverser les fichiers "Sol_Cavite2D_Reynolds=**Nombre_de_Reynolds**_0.vtu sur Paraview.

## Résultats 
https://github.com/Ronfleex/Research_Lungs/assets/129523736/d92193a0-70b6-42a4-85c1-84148d34d7c0
