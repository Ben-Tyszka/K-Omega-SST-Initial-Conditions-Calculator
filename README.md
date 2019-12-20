# K-ω SST Initial Conditions Calculator
### This MATLAB app solves the equations that yeild the turbulent kinetic energy and specific turbulent dissipation rate (K, ω respectively) for the K-ω SST RANS turbulence model.

## Background
The Reynolds-averaged Naiver-Stokes (RANS) equations are used to approximate a time-averaged solution to the Naiver-Stokes equations so long as certain properties of flow turbulence are known/smartly approximated. Among the most common and useful turbulent models to do so is the Shear Stress Transport (SST) variant of the K-ω turbulence model. K-ω SST handles walls within flows exceptionally well, and as such is used extensively in engineering practice. It is the model of choice for many situations when running computational fluid dynamics (CFD) simulations.

## App Purpose
K-ω requires two initial condition parameters to output accurate CFD results:
- K: The Turbulent Kinetic Energy
- ω: Specific turbulent dissipation rate

These properties are calculated based on the characteristics of the wall within the flow, and some approximation is used in their calculation.
