# MIL-100-Second-Sphere-Coordination-Effects

This repository contains files for the paper *Second Sphere Coordination Effects in Redox Turnovers over Highly Uniform Supported Polymetal Oxo Clusters*. 

The repository is organized according to the following: 
* [00-Example-Gaussian-Inputs](https://github.com/getman-research-group/MIL-100-Second-Sphere-Coordination-Effects/tree/main/00-Example-Gaussian-Inputs): A sample gjf file for each type of the calculations performed. 
  * example-opt.gjf: geometry optimization
  * example-stable.gjf: stability calculation
  * example-freq.gjf: frequency calculation 
  * example-TS.gjf: transition state calculation that calculates the force at every step
  * example-counterpoise.gjf: counterpoise calculations to determine the Basis Set Superposition Error (BSSE)
  * example-broken1.gjf: broken symmetry example calculation to define alpha and beta electron spin states using fragments
  * example-broken2.gjf: broken symmetry example SCF calculation from electron density guess from broken2
* [01-TZVP_basis_set_files](https://github.com/getman-research-group/MIL-100-Second-Sphere-Coordination-Effects/tree/main/01-TZVP_basis_set_files): All of the TZVP basis set files used in the analysis
* [02-G16-Log-Files](https://github.com/getman-research-group/MIL-100-Second-Sphere-Coordination-Effects/tree/main/02-G16-Log-Files): The log files for the different Fe3O calculations
