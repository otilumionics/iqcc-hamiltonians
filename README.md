# iqcc-hamiltonians
[![DOI](https://zenodo.org/badge/657659129.svg)](https://zenodo.org/doi/10.5281/zenodo.10961200)


Hamiltonians generated using the iterative Qubit Coupled Cluster (iQCC) method for use in quantum chemistry simulations.


This repository contains Hamiltonians of select systems generated from a modified version of GAMESS. The style and format of these Hamiltonians are human readable, but are organized in a right to left format in qubit basis. Each package contains the electronic Hamiltonian and auxiliary Hamiltonians of the number and spin operators which are intended to be used as described in this publication: https://doi.org/10.1021/acs.jctc.8b00943

Outputs from various iQCC simulations are also posted here, where additional files that contain energy and entangler information are available. Entangler sets are generated as described in the following publication: https://doi.org/10.1021/acs.jctc.8b00932


File index: All Hamiltonians are in right to left format

- H_1.inp - Electronic Hamiltonian
- N_1.inp - Number operator
- Npenalty_1.inp - Number penalty operator
- S2_1.inp - Spin operator
- Spenalty_1.inp - Spin penalty operator
- Sz_1.inp - Sz operator
- reference_state.inp - file containing information about the Hamiltonian generation including coefficient cutoffs and the initial occupation reference vector

# iqcc output files

Output files are occasionally updated when new publications are made available. Simulation outputs can varry depending on the inputs to the iQCC algorithm and this information is contained either within the outputfile or within the Readme file. 

Output files follow a format that shows the "QMF" state for the iQCC iteration Hamiltonian, followed by the PT and DUC energy corrections, then followed by the list of the entanglers used for the iQCC iteration listed with their importance factor, then finally an array of the optimized amplitudes. 

# citation
When using any information from this repository the following publications must be cited as it describes the process in which the entanglers were generated:
https://doi.org/10.1021/acs.jctc.8b00932 
https://doi.org/10.1021/acs.jctc.9b01084

Additional publications to cite will be noted in the sub-directories
