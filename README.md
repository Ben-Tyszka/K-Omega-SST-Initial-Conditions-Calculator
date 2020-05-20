# K-ω SST Initial Conditions Calculator
### This MATLAB app solves the equations that yeild the turbulent kinetic energy and specific turbulent dissipation rate (K, ω respectively) for the K-ω SST RANS turbulence model.

## Background
The Reynolds-averaged Naiver-Stokes (RANS) equations are used to approximate a steady-state numerical solution to the Naiver-Stokes equations so long as certain properties of flow turbulence are known/smartly approximated. Among the most common and useful turbulent models to do so is the Shear Stress Transport (SST) variant of the K-ω turbulence model. K-ω SST handles pipe flows and single walls within flows exceptionally well, and as such is used extensively in engineering practice. It is the model of choice for many situations when running computational fluid dynamics (CFD) simulations.

## App Purpose
The K-ω turbulance model requires the following known initial condition parameters to output accurate CFD results:
- K: The turbulent kinetic energy of the working fluid
- ω: The specific turbulent dissipation rate of the working fluid

These properties are calculated based on the characteristics of the wall within the flow and known properties of the working fluid.
