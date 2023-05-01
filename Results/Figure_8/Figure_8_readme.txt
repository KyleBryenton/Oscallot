Kyle Bryenton 2023-01-04

C6 and Energy scans for Methane Dimer, Benzene Dimer, Graphite exfoliation, and MoS2 exfoliation.

Data is presented as one system per .dat

Rows separate the functional/correction used

Columns separate the displacement
- Benzene & Methane: Coarse scan is in terms of S22x5 data, Fine scan revisits points near equilibrium separation. The columns indicate the scale factor (where 10=1.0, and 100=1.00 for coarse and fine scan respectively)
- Graphite & MoS2: The columns indicate a displacement of the layers in bohr, negative being closer together, positive being further apart. The datapoint at 8.0 was dropped due to numerical issues with the FHI-aims code for interlayer separations near this value.

C6s are given in a.u., Energies are given in eV.

For the C6s, "MBD_C6" indicates the starting point for MBD, which is the TS method. "MBD_SCS" indicates the C6 value after the rsSCS process.
For the energies, TS was added explicitly. 

For the MoS2 energy, MBD failed to converge in its energy calculation step, so all energies have been replaced with 0.