The code is coded in C++ using FreeFEM++. It includes the Navier-Stokes solution with special features to understand how air flows in a square with predefined edge conditions.

To get a better understanding of how this works, we have worked on a number of different scenarios, which we will later visualise using Paraview.

|Reynolds number| Mesh size (NxN)| Boundary conditions (U0)| Results / Observations |
| --------- | --------- | --------- |--------- |
| 100 | 50x50 | U0 = 1 sur le bord supérieur | Laminar regime, stable flow. ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/c42ee93d-a682-48a1-a20a-5b9162c7ed88)
| 400 | 50x50 | U0 = 1 sur le bord supérieur | ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/ba0c4519-0853-467d-b845-45790d04a8e0)
| 5000 | 50x50 | U0 = 1 sur le bord supérieur | Swirl in the centre ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/d899c0d6-6095-47a0-9d81-dd0d72b726ac)
| 100 | 100 x 100 | U0 = 1 sur le bord supérieur | ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/ab0b5f7d-c4b4-47c6-a52c-05e02aadbe2c)
| 400 | 100 x 100 | U0 = 1 sur le bord supérieur | ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/0695d88a-4245-40fd-8a53-c17377f44607)
| 1000 | 100 x 100 | U0 = 1 sur le bord supérieur | ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/a58090a7-ff83-407f-a24c-731ff8a0527f)
| 400 | 100 x 100 | U0 = 0 sur le bord supérieur, U0 = 1 sur le côté droit | Unstable flow 
| 1000 | 100 x 100 | U0 = 0 sur le bord supérieur, U0 = 1 sur le côté droit | Unstable flow
| 100 | 100 x 100 |U0 = 1 sur le bord supérieur, U0 = 1 sur le côté droit | ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/52349a8c-b067-46ab-b7ed-a18401e06008)
| 400 | 100 x 100 |U0 = 1 sur le bord supérieur, U0 = 1 sur le côté droit,  U0 = 1 sur le côté gauche | ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/00e8c340-339e-4ea2-aa67-5da0d9fbea53)
| 1000 | 100 x 100 |U0 = 1 sur le bord supérieur, U0 = 1 sur le bord inférieur | ![image](https://github.com/Ronfleex/Research_Lungs/assets/129523736/3617c05e-5992-46fe-a694-5b3188f647e2)


We can see that the code works well. Depending on the Reynolds number, the mesh size or the boundary conditions imposed, it is possible to move from a laminar to a turbulent regime, to achieve greater precision (and therefore computation time) with a larger number of meshes in the square, or even to have a different flow according to the different U0 edge boundaries.
