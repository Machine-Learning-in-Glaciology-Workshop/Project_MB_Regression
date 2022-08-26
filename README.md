# Physics-based machine learning for glacier modelling

**Authors:** <br />
Jordi Bolibar <br />
Facundo Sapienza

Materials for regression methods from the Machine learning for Glaciology workshop, held at the Finse research station (Norway).
In this part of the workshop, the basics of regression methods applied to glaciological problems are covered, with a focus
on adding physical constraints in models. These are separated between a presentation covering some theoretical aspects, and 
a series of Jupyter notebooks showing practical aspects through a project. 

> All these materials will be updated throughout the different iterations of the workshop. If you encounter any errors or typos,
feel free to make a pull request!

## Theory
[The presentation](https://github.com/Machine-Learning-in-Glaciology-Workshop/Mass_Balance_ML_modelling/raw/main/Presentation_PhysicsBased_ML_Glaciology.pptx)
introduces students to the general concepts of a machine learning pipeline. How to properly design a dataset, how to correctly
train models and how validate, test and understand the capabilities and limitation of the model(s). 

The following contents are covered:

- **Modelling the glacier system**
  - Glacier evolution models
  - Local vs Global glacier modelling
  
- **Physics-based machine learning**
  - Machine learning pipelines
  - Regression for physical processes
    - Respecting physics
      - Feature selection
      - Data driven machine learning
      - Physical losses or Physics-Informed Neural Networks
      - Neural/Universal Differential Equations
    - Trustworthy models
      - Testing and validation
      - Physical interpretation
    - Being mindful about model limitations
- **Project description**

## Project

The project consists on a series of Jupyter notebooks in Python, focused on glacier mass balance modelling using different types of 
regression methods. Data is extracted using the [Open Global Glacier Model (OGGM)](https://github.com/OGGM/oggm), providing climate, topographical and 
mass balance data for almost any glacier on Earth. The project is focused on all glaciers in Scandinavia, with the goal
of learning multi-annual mass balance changes from [the Hugonnet et al. (2021)](https://www.nature.com/articles/s41586-021-03436-z ) 
geodetic mass balance paper. We cover two of the most popular machine learning libraries for beginners: 
[scikit-learn](https://scikit-learn.org/stable/) and [Keras](https://keras.io/).

