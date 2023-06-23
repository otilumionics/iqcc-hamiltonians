# iqcc-hamiltonians
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
