# DFT
Quantum ESPRESSO (QE)
Run pw.x in self consistent mode for silicon.
pw.x < pw.scf.silicon.in > pw.scf.silicon.out
# For parallel execution
mpirun -np 4 pw.x -inp pw.scf.silicon.in > pw.scf.silicon.out
