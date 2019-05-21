# StructJuMP Demo

This repository contains a demo of the [StructJuMP](https://github.com/Argonne-National-Laboratory/StructJuMP.jl) algebraic modeling package for two-stage stochastic optimization. It goes over three examples. The first one is a general introduction on how to use StructJuMP while the last two use cases are AC optimal power flow (ACOPF) and security constrained ACOPF (SCOPF).

## Requirements

* Julia >= 0.7
* MPI library (MPICH, OpenMPI, ...)

## Installation

A [Julia environment](https://docs.julialang.org/en/v1/stdlib/Pkg/index.html) is provided that needs to be activated and instantiated. `]` needs to be pressed to enter the Julia package manager.
```julia
] activate .
instantiate
```
This installs all the dependencies of StructJuMP.

## Examples

The examples are provided as Jupyter notebooks.

### Generic Example

### AC Optimal Power Flow

AC optimal power flow (ACOPF) is the basic block composing the two-stage SCOPF that will follow.

Files

* `opfdata.jl`: Load grid data.
* `acopf.jl`: Contains the opf model, initialization, the call to the solver, and the displaying of the output.
* `acopf.ipynb`: Jupyter notebook to play with the `acopf` functionality.

### Security Constrained Optimal Power Flow

