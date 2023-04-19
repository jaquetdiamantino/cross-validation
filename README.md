# Overview

This repository contains the experiments of the paper:

*Diamantino et. al. 2023. How difficult is variogram selection with cross-validation?*.

## Instructions

1. Download and install [Julia ≥ v1.8.5](https://julialang.org/downloads/).

2. Open Julia REPL and install [Pluto](https://github.com/fonsp/Pluto.jl):
```julia
julia> import Pkg
julia> Pkg.add("Pluto")
```
3. Clone or download this repository.

4. Launch Pluto:
```julia
julia> import Pluto
julia> Pluto.run()
```
5. Select the notebook of interest:

- `experiment.jl`: cross-validation experiment
- `survey.jl`: post-processing of survey results

## Results

### Deposit 1

#### Regular Samples and Clustered Samples

![deposit1](results/deposit1.png) 

#### Error estimates obtained through *k-fold* and *leave-one-out* cross-validation applying the three spacings and candidate variograms

![dep1-boxplots](results/dep1-boxplots.png) 

### Deposit 2

#### Regular Samples and Clustered Samples

![deposit2](results/deposit2.png) 

#### Error estimates obtained through *k-fold* and *leave-one-out* cross-validation applying the three spacings and candidate variograms

![dep2-boxplots](results/dep2-boxplots.png) 
