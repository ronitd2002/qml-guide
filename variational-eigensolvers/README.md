# Variational Eigensolvers:

Simply speaking steps - 
1. Data encoding : The encoding of the data (problem specific)

2. Ansatz : Series of rotational gates with tunable and training paramters and entanglement gates. Define a parameterized ansatz (might face initial ansatz probelms, if it does test with other ansatzes)

3. Cost function to be minimized. Usually the expectation value of the hamiltonian operator whose energy is required to be found.

4. Gradient Optimizer function: Can be one of the several from SPSA, standard GDO, Stochastic GDO, COBYLA etc