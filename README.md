# Overview

This repository contains the experiments of the paper:

*Diamantino et. al. 2023. How difficult is variogram selection with cross-validation?*.

## Instructions

1. Download and install [Julia ≥ v1.8.5](https://julialang.org/downloads/).

2. Open Julia REPL and install [Pluto](https://github.com/fonsp/Pluto.jl):
```julia
julia> using Pkg
julia> Pkg.add("Pluto")
```
3. Clone or download this repository.

4. Launch Pluto:
```julia
julia> using Pluto
julia> Pluto.run()
```
5. From the root folder of the project:

```bash
# Experiment
$ julia --project experiment.jl

# Survey
$ julia --project survey.jl
```

