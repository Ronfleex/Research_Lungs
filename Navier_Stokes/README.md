Le code est codé en C++ via FreeFEM++. Il comprend la solution de Navier-Stokes avec des particularités afin de comprendre comment l'écoulement de l'air se fait dans un carré avec les conditions aux bords au préalable définis.

Pour mieux comprendre comment cela fonctionne, nous avons travaillé sur différents cas de figure que nous visualiserons par la suite grâce à Paraview. 

| Nombres de Reynolds| Taille du maillage (NxN)| Conditions aux limites (U0)| Résultats / Observations |
| --------- | --------- | --------- |--------- |
| 100 | 50x50 | U0 = 1 sur le bord supérieur | Régime laminaire, écoulement stable. ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/c42ee93d-a682-48a1-a20a-5b9162c7ed88)
| 400 | 50x50 | U0 = 1 sur le bord supérieur | ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/ba0c4519-0853-467d-b845-45790d04a8e0)
| 5000 | 50x50 | U0 = 1 sur le bord supérieur | Tourbillon au centre ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/d899c0d6-6095-47a0-9d81-dd0d72b726ac)
| 100 | 100 x 100 | U0 = 1 sur le bord supérieur | Plus de détails dans l'écoulement laminaire ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/ab0b5f7d-c4b4-47c6-a52c-05e02aadbe2c)
| 400 | 100 x 100 | U0 = 1 sur le bord supérieur | ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/0695d88a-4245-40fd-8a53-c17377f44607)
| 1000 | 100 x 100 | U0 = 1 sur le bord supérieur | ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/a58090a7-ff83-407f-a24c-731ff8a0527f)
| 400 | 100 x 100 | U0 = 0 sur le bord supérieur, U0 = 1 sur le côté droit | Ecoulement instable 
| 1000 | 100 x 100 | U0 = 0 sur le bord supérieur, U0 = 1 sur le côté droit | Ecoulement instable
| 100 | 100 x 100 |U0 = 1 sur le bord supérieur, U0 = 1 sur le côté droit | ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/52349a8c-b067-46ab-b7ed-a18401e06008)
| 400 | 100 x 100 |U0 = 1 sur le bord supérieur, U0 = 1 sur le côté droit,  U0 = 1 sur le côté gauche | ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/00e8c340-339e-4ea2-aa67-5da0d9fbea53)
| 1000 | 100 x 100 |U0 = 1 sur le bord supérieur, U0 = 1 sur le bord inférieur | ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/3617c05e-5992-46fe-a694-5b3188f647e2)




