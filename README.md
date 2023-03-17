# Project: Machine learning for glacier mass balance modelling

**Authors:** <br />
Jordi Bolibar <br />
Facundo Sapienza

## Project description

The project consists on 4 Jupyter notebooks in Python, focused on glacier mass balance modelling using different types of 
regression methods. Data is extracted using the [Open Global Glacier Model (OGGM)](https://github.com/OGGM/oggm), providing climate, topographical and 
mass balance data for almost any glacier on Earth. The project is focused on all glaciers in Scandinavia, with the goal
of learning multi-annual mass balance changes from [the Hugonnet et al. (2021)](https://www.nature.com/articles/s41586-021-03436-z ) 
geodetic mass balance paper. We cover one of the most popular machine learning libraries for beginners: 
[scikit-learn](https://scikit-learn.org/stable/).

The following topics are covered in this project:

1. [Data pre-processing](https://github.com/Machine-Learning-in-Glaciology-Workshop/Project_MB_Regression/blob/main/1_Preprocessing.ipynb) :earth_africa:: Here we learn how to extract all the necessary climate, topographical and mass balance data for any glacier on Earth using OGGM. 

2. [Data exploration](https://github.com/Machine-Learning-in-Glaciology-Workshop/Project_MB_Regression/blob/main/2_Data_exploration.ipynb) :mag:: Here we learn how understand the dataset we have compiled, what are the assumptions behind it, and how to correctly construct a good dataset for regression machine learning models of physical processes. 

3. [Training](https://github.com/Machine-Learning-in-Glaciology-Workshop/Project_MB_Regression/blob/main/3_Training.ipynb) :rocket:: Here we introduce the different machine learning methods that we can use to simulate glacier mass balance. We will explore the characteristics of each one, including their specific hyperparameters. 

4. [Validation](https://github.com/Machine-Learning-in-Glaciology-Workshop/Project_MB_Regression/blob/main/4_Validation.ipynb) :dart:: Once we are acquainted with the different machine learning models, we will introduce the concepts of cross-validation and hyperparameter selection. We will choose one of the models, which we will tune in detail in cross-validation in order to correctly extrapolate for unseen data. 
