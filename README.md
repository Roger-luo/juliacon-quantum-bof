# JuliaCon 2020 Quantum BoF Materials
Materials for Quantum BOF in JuliaCon 2020

## Abstract

Chat about [Yao](http://yaoquantum.org/), [ITensor](https://github.com/ITensor/ITensors.jl), [TensorOperations](https://github.com/Jutho/TensorOperations.jl), [OMEinsum](https://github.com/under-Peter/OMEinsum.jl) and development on common infrastructure such as lattices, sparse tensor, domain specific automatic differentiation etc. in Quantum Physics.

## Description

Topics to discuss:

- A Julian lattice package
- what else do you want in Yao.jl?
- sharing quantum state objects between QuantumOptics.jl, QuantumInformation.jl, Yao.jl and others.
- Status of Julia library support for specialized tensor operation backends
  * CuTensor support in CuArrays
  * Support for TBLIS, GETT and similar?
  * Algorithms people want (TDVP, TEBD, tDMRG, any four letter acronym like this)
- Domain specific automatic differentiation (AD)
  * AD through SVD in Julia libraries such as Zygote
  * A one for all solution to AD - Reversible Programming.
- GPU stuff
  * multi GPU parallelism
  * exploiting mixed precision for some quantum libraries
- Tutorial writing
- Julia quantum as a teaching tool - interactive graph demos?
- Benchmarking within the Julia community and compared to other packages
- Brief report of the maintainace of OMEinsum.
- Brain Storm: Generic elements in a tensor network/quantum simulator.
  * Tropical Numbers: https://gist.github.com/GiggleLiu/db9efa143aefbbe1d542e7b78d3a65bc
  * Dual numbers
  * Counting Tropical numbers
  * More?
