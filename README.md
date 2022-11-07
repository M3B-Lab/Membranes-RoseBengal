# Membranes-RoseBengal

This repositary contains the simulation data for the paper "Cellular uptake of rose bengal is mediated by OATP1B1/1B3 transporters".

The input data, required to reproduce the results in the paper, is organized in the following folders:

 * `MDP/`

  This folder contains the MD simulation parameters in GROMACS MDP format used for minimization, stepwise equilibration and production MD simulation.

 * `Topologies/`

  This folder contains the molecular topologies for the simulated membrane (as obtained from CHARMM-GUI) and the CGenFF topology for Rose Bengal.

 * `SimulationInput/`

  This folder contains the input coordinates (in both PDB and TPR format) for the production MD simulations (after NVT+NPT equilibration).
