# quasispecies-evolution-model
This repository contains the computational framework developed for my **Bachelor's Thesis (TFG) in Biochemistry**. The project focuses on the mathematical modeling and simulation of Eigen's quasispecies model with alphabet size b > 2, typically b = 4.

## Overview 
Quasispecies are sequences characterized by high mutation rates, existing as a "cloud" of closely related variants. This project implements Python to study:
* the error catastrophe phenomenon, using Shannon's entropy as a general variable to define how information is lost/maintained in time.
* the effect stochastic mutation rates have in characteristic transition times.
* how population-dependent fitness landscapes generate temporal imbalance within distinct quasiespecies.

## Features
* Built from scratch to handle multitude of different parameters (length, cardinality, mutation rates distribution, etc).
* Data Production: Scripts generate timestamped and parameter-specific directories with SSV files for streamlined data analysis and visualization.
  
**Languages**: Python (numpy, scipy, matplotlib).
**Methods**: Deterministic (odeint, manually implemented RK4). Stochastic (Gillespie algorithm).

## Academic Context
Universidad Complutense de Madrid (UCM). Madrid, Spain.
Dept. of Biochemistry and Molecular Biology. Group of Biophysics and Systems Biology.
(Project supported by a **Collaboration Grant from the Spanish Ministry of Education**)

*Developed as part of a Double Degree in Chemistry and Biochemistry.*

