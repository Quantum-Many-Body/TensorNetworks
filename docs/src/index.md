```@meta
CurrentModule=TensorNetworks
```

# TensorNetworks

*Julia package for the tensor networks in condensed matter physics.*

This package provides definitions and methods of dense and sparse multi-labeled tensors. Based on this, common tensor networks in condensed matter physics with different structures are defined, such as the matrix product states (MPS), matrix product operators (MPO), etc. Construction of these tensor networks from a usual fermionic/hard-core-bosonic/spin system is also supported, which depends on the **symbolic operator representation** of a quantum lattice system that is generated by the package [`QuantumLattices`](https://github.com/Quantum-Many-Body/QuantumLattices.jl).

## Python counterpart
[HamiltonianPy](https://github.com/waltergu/HamiltonianPy): in fact, the authors of this Julia package worked on the python package at first and only turned to Julia later.
