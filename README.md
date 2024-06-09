## Project Description and Control Objectve

Continuous stirred tank mixing process with two inlet F1 and F2 with the different concentration C1 and C2 has been taken for modeling and optimization. For the system, I have taken the assumption that CSTR has well mixed as well as the outlet concentration (C) at output stream (F) is same as the tank concentration. The aim of the project is to control the outlet concentration while maintain the height of the tank with respect to the change in the inlets flow F1 and F2 as well as the inlets stream concentration C1
and C2 respectively
![image](https://github.com/AbhiChauhan07/Optimal_Predictive_Control/assets/156859411/00f29889-18e8-4bd6-8a3e-8e0e2ccd1c16)

### Terminology:
+ `LQR` (Linear Qudaratic Regulator) - Liniearization of the system and stabilize the system around the SS values.
+ `TPBVP` (Two Point Boundry Value Problem) - Impliment the boundry condtion on the system and solve the control problem.
+ `MPC` (Model Predictive Control) - solves a problem related to optimal control using the system's current state as a starting state and forecasts the set of control actions for a finite amount of time.
