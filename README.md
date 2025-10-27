Predicting Bridge Deflection Under Moving Loads Using Physics-Informed Neural Networks (PINN)

This project is based on the paper “Developing Physics-Informed Neural Networks for Virtual Sensing in Beams with Moving Loads” by Al-Adly and Kripakaran (2025). The study introduced a Physics-Informed Neural Network (PINN) framework to predict the structural response of bridges subjected to a moving concentrated load. In this project, Case Study 1 from the paper is reproduced and enhanced by replacing the soft-constraint PINN with a hard-constraint PINN formulation. The soft-constraint approach incorporates governing equations, boundary conditions, and initial conditions as penalty terms in the loss function. The hard-constraint approach enforces these conditions exactly using a trial-solution formulation, eliminating the need for boundary and initial condition penalties. The objective is to evaluate how constraint enforcement methods affect model prediction accuracy when modeling beam deflection under moving loads. Comparisons with analytical solutions demonstrate that the hard-constraint PINN achieves improved accuracy and better compliance with physical boundary conditions.

Authors:
Aldio Wahyu Pratama
Ashish Kumar
