
### Lung_2D_V4_Respiratory_Tract

Le code est en C++ via FreeFEM++.

## Introduction

Le poumon a une structure géométrique complexe. Dans ce code, on retrouve le maillage du poumon du quatrième niveau. On a ajouter à cela le code de Navier-Stokes afin de pouvoir observer l'écoulement dans le poumon tout en travaillant sur les conditions aux limites.

Pour les conditions aux limites, nous travaillons avec types de bords différents avec chacun leur propre labels :

- Label 0 : Sortie 0 ou entrée (la bouche)
- Label 1 : Sortie numéro 1
- Label 2 : Sortie numéro 2
- Label 3 : Sortie numéro 3
- Label 4 : Sortie numéro 4
- Label 5 : Sortie numéro 5
- Label 6 : Sortie numéro 6
- Label 7 : Sortie numéro 7
- Label 8 : Sortie numéro 8
- Label 9 : Sortie numéro 9
- Label 10 : Sortie numéro 10
- Label 11 : Sortie numéro 11
- Label 12 : Sortie numéro 12
- Label 13 : Sortie numéro 13
- Label 14 : Sortie numéro 14
- Label 15 : Sortie numéro 15
- Label 16 : Sortie numéro 16
- Label 20 : tout les bords latérals 

![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/7ecede65-f422-4793-83fc-72d38a151bac)


## Utilisation

Pour faire fonctionner le code, plusieurs variables sont changeables comme le nombre de Reynolds, le pas de temps, les conditions aux limites. Pour visualiser l'animation, il faut téléverser les fichiers "Sol_Cavite2D_Reynolds=**Nombre_de_Reynolds**_0.vtu sur Paraview.

## Résultats 

https://github.com/Ronfleex/Research_Lungs/assets/129523736/d36d6769-cd39-4a2d-a304-a7b9d9f4f856
