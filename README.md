# Membranes-RoseBengal

This repositary contains the simulation data for the paper "Cellular uptake of rose bengal is mediated by OATP1B1/1B3 transporters".

The input data, required to reproduce the results in the paper, is organized in the following folders:

 * `MDP/`

  This folder contains the MD simulation parameters in GROMACS MDP format used for minimization, stepwise equilibration and production MD simulation.

 * `Topologies/`

  This folder contains the molecular topologies for the simulated membrane (as obtained from CHARMM-GUI) and the CGenFF topology for Rose Bengal.

 * `SimulationInput/`

  This folder contains the input coordinates (in both PDB and TPR format) for the production MD simulations (after NVT+NPT equilibration).

---

# Acknowledgements:
*CHARMM-GUI*:

S. Jo, T. Kim, V.G. Iyer, and W. Im (2008)
CHARMM-GUI: A Web-based Graphical User Interface for CHARMM. J. Comput. Chem. 29:1859-1865 

B.R. Brooks, C.L. Brooks III, A.D. MacKerell, Jr., L. Nilsson, R.J. Petrella, B. Roux, Y. Won, G. Archontis, C. Bartels, S. Boresch, A. Caflisch, L. Caves, Q. Cui, A.R. Dinner, M. Feig, S. Fischer, J. Gao, M. Hodoscek, W. Im, K. Kuczera, T. Lazaridis, J. Ma, V. Ovchinnikov, E. Paci, R.W. Pastor, C.B. Post, J.Z. Pu, M. Schaefer, B. Tidor, R. M. Venable, H. L. Woodcock, X. Wu, W. Yang, D.M. York, and M. Karplus (2009)
CHARMM: The Biomolecular Simulation Program. J. Comput. Chem. 30:1545-1614 

J. Lee, X. Cheng, J.M. Swails, M.S. Yeom, P.K. Eastman, J.A. Lemkul, S. Wei, J. Buckner, J.C. Jeong, Y. Qi, S. Jo, V.S. Pande, D.A. Case, C.L. Brooks III, A.D. MacKerell Jr, J.B. Klauda, and W. Im (2016)
CHARMM-GUI Input Generator for NAMD, GROMACS, AMBER, OpenMM, and CHARMM/OpenMM Simulations using the CHARMM36 Additive Force Field. J. Chem. Theory Comput. 12:405-413 
