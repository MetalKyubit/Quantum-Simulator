# Quantum-Simulator

The program is run by calling the simulator function. The initial state in the form of a 2^16 dimension list and the QASM Benchmark file location in the form of string are given as inputs to the simulator function. The initial state list contains the amplitudes of all the input states in order. The representation of qubits is such that the index of the element of ‘initial state list’ in binary of 16 digits is the state of the qubits. The order of the qubits is the same as that followed by python, that is, the leftmost digit in binary represents qubit 0 and the rightmost binary digit represents qubit 16.

\n The functions of different gates are prepared in the python notebook. These functions are called by the simulator function whenever they need to be implemented.
\n The simulator function is the function that is to be used. The output of this function is the final state list of the final state that follows same representation as the initial state list (elements store the amplitudes of the different possible states of the qubits).
\n When the function is run it pritns the final state and prints the state of the qubits after each step. The final state is printed in dirac notation with complex number amplitudes.
