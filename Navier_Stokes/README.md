Le code est codé en C++ via FreeFEM++. Il comprend la solution de Navier-Stokes avec des particularités afin de comprendre comment l'écoulement de l'air se fait dans un carré avec les conditions aux bords au préalable définis.

Pour mieux comprendre comment cela fonctionne, nous avons travaillé sur différents cas de figure que nous visualiserons par la suite grâce à Paraview. 

| Nombres de Reynolds| Taille du maillage (NxN)| Conditions aux limites (U0)| Résultats / Observations |
| --------- | --------- | --------- |--------- |
| 100 | 50x50 | U0 = 1 sur le bord supérieur | Régime laminaire, écoulement stable. ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/10b4b61c-175f-4347-a4e9-34d5636d4d1a)

| Ligne 2, Cellule 1 | Ligne 2, Cellule 2 | Ligne 2, Cellule 3 |
| Ligne 3, Cellule 1 | Ligne 3, Cellule 2 | Ligne 3, Cellule 3 |

