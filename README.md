# Research_Lungs

As part of my master degree, I had the opportunity to join the research track. My research subject is about the numerical modelling of airflow in the respiratory tract using FreeFEM++ for numerical modelling and Paraview for visual analysis.

# Context

The human lung has a fairly complex and atypical geometric structure. In medical imaging, it is difficult to visualise the entire lung. In fact, we can only see the upper part of the lung. The idea of the research is to propose a numerical approach to be able to visualise the part non-visible on the medical imaging.

To recreate as closely as possible the simulation of the human lung in reality, there are a number of physical concepts to be taken into account :Navier-Stokes,convective term,temperature effect,... which allows to play the rigidity of the lung (via the force) during exhalation to be taken into account. In our case, we also want to work on the asthma case pathology with the idea to test our simulation in a specific situation.

# GitHub structure

To see how the project is constructed, I divide the code into several sections so that I can follow the project's progress and test all the features:

- **Navier-Stokes**: The idea is to be able to learn how works FreeFEM++, understand how Navier-Stokes works, how to code it and how the simulation reacts in different cases.
- **Lung_2D_V1**: The idea is to be able to mesh the Lung on FreeFEM++.
- **Lung_2D_V2**: The idea is to be able to mesh the Lung on FreeFEM++.
- **Lung_2D_V3**: The idea is to be able to mesh the Lung on FreeFEM++.
- **Lung_2D_V4**: The idea is to be able to mesh the Lung on FreeFEM++.
- **Lung_2D_NS_Expiration/Inspiration** : The idea is to be able to mesh the Lung on FreeFEM++ with Navier-Stokes and to add to the code the breathing cycle as in reality.
- **EulerImplicit_NS** : The idea is to work on the Splitting method (ImplicitEuler) on Navier_Stokes.
- **EulerImplicit_Total** : The idea is to work on the splitting method via ImplicitEuler with the final formula written in the paper.
- **EulerImplicit_Total_Lung**: The idea is to work on the splitting method via ImplicitEuler with the final formula, testing several cases in order to keep the most optimal one.
- **NS+EulerImplicit+Lung combination** : The idea is to be able to simulate in a lung filled with air with all the previous constraints.
- **Lung_2D_Temperature effect**: The idea is to add the temperature effect to the formula/simulation. 
- **Asthma**: The idea is to be able to test the simulation with a pathology for which a state of the art has been carried out beforehand.


# Updates

Currently, I am working on the EulermImplicitComparative and on the temperature effect in the Lung_2D_V4 version. 
