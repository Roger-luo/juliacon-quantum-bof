# JuliaCon 2020 Quantum BoF Materials
Materials for Quantum BOF in JuliaCon 2020

## Abstract

Chat about [Yao](http://yaoquantum.org/), [ITensor](https://github.com/ITensor/ITensors.jl), [TensorOperations](https://github.com/Jutho/TensorOperations.jl), [OMEinsum](https://github.com/under-Peter/OMEinsum.jl) and development on common infrastructure such as lattices, sparse tensor, domain specific automatic differentiation etc. in Quantum Physics.

## Description

## Self Intro

## Priority Topics
- Domain specific automatic differentiation (AD)
  * AD through SVD in Julia libraries such as [Zygote](https://github.com/FluxML/Zygote.jl)
  * A one for all solution to AD - Reversible Programming [NiLang](https://github.com/FluxML/Zygote.jl).
- GPU stuff
  * multi GPU parallelism [CUDA](https://github.com/JuliaGPU/CUDA.jl)
  * exploiting mixed precision for some quantum libraries
- Brief report of the maintainace of [OMEinsum](https://github.com/under-Peter/OMEinsum.jl).
- what else do you want in [Yao.jl](https://github.com/QuantumBFS/Yao.jl)? your wishlist for quantum computing in Julia.
- quantum circuit simulation
- quantum control (Alastair)

## Ask around
- sharing quantum state objects between [QuantumOptics.jl](https://github.com/qojulia/QuantumOptics.jl), [QuantumInformation.jl](https://github.com/iitis/QuantumInformation.jl), Yao.jl and others.
- A Julian lattice package [Lattices.jl](https://github.com/JuliaPhysics/Lattices.jl)

## Other Topics to discuss:

- Status of Julia library support for specialized tensor operation backends
  * CuTensor support in CuArrays
  * Support for TBLIS, GETT and similar? *
  * Algorithms people want (TDVP, TEBD, tDMRG, any four letter acronym like this)
- Tutorial writing
- Julia quantum as a teaching tool - interactive graph demos? *
- Benchmarking within the Julia community and compared to other packages *

## Brain Storm 
- Brain Storm: Generic elements in a tensor network/quantum simulator.
  * Tropical Numbers: https://gist.github.com/GiggleLiu/db9efa143aefbbe1d542e7b78d3a65bc
  * Dual numbers
  * Counting Tropical numbers
  * More?

