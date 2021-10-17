# Electrochemical-Thermal-Simulation
This repository contains data and code for developing a fast and accurate electrochemical-thermal coupled battery model

Please go to readme.txt before viewing the files in each folder.

In this work, we propose an adaptive spectral method to reformulate an electrochemical-thermal coupled battery model. By discretizing the governing equation according to the lithium-ion concentration gradient and introducing a differentiation matrix, both the computational efficiency and model accuracy are improved significantly. The proposed reformulation method is also applicable to other problems involving partial differential equations, such as degradation and stress-strain models.

In this version, all the codes were written using 'Mathematica®'. Also, the single-step iteration-free initialization approach is used to find the consistent initial conditions.
This code is intended solely for academic and teaching purposes. 
The single-step iteration-free initialization approach is protected under the U.S. Patent, US10769236B2, USA, 2020. If this code is used for commercial purposes, it might infringe on the original patent of the single-step iteration-free initialization.

We also wrote this code in matlab® environment, and the single-step iteration-free initialization approach is not used. This version of code is available upon reasonable request.
