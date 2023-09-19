**Computing equilibrium free energies through a nonequilibrium quench**

**(Kangxin Liu, Grant Rotskoff, Eric Vanden-Eijnden, and Glen Hocky)**

This repository contains the python framework for performing quench simulations using LAMMPS.
Three systems are tested in quench simulations:
1. independent harmonic springs system

Codes are available in the folder *quench_spring*

2. alanine dipeptide in vacuum

In the folder *ref_umbrella*, a reference FES of alanine dipeptide in vacuum on 2D CV $(\phi,\psi)$ is calculated from umbrella sampling simulations biasing along $(\phi,\psi)$ and reweighted by WHAM. In the folder *ref_umbrella_psi*, a reference FES on $(\phi,\psi)$ is calculated from umbrella sampling simulations biasing along the bad CV $\psi$ reweighted by WHAM. Corresponding FES computations using quench simulations, quench + umbrella sampling simulations biasing along $(\phi,\psi)$ or $\psi$ are performed in the folder *quench_alanine, quench_umbrella, quench_umbrella_psi* respectively.

3. alanine dipeptide in water

In the folder *ref_solv_umbrella*, a reference FES of alanine dipeptide in water on 2D CV $(\phi,\psi)$ is calculated from umbrella sampling simulations biasing along $(\phi,\psi)$ and reweighted by WHAM. Corresponding FES computations using quench + umbrella sampling simulations biasing along $(\phi,\psi)$ are performed in the folder *quench_solv_umbrella*.
