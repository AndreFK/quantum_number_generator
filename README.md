# Quantum Number Generator

##### A true random number generator using H Gates (Hadamard gates) with Qiskit.

Creates a quantum circuit with 8 qubit registers to produce the random number and 8 classic bit registers to store the results.

First uses _qasm_simulator_ to generate a set of random numbers, then it connects to a quantum computer from IBM to generate another
set of random numbers with real quantum mechanics.