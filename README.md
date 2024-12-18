# ILMPostProcessing.jl
_Tools for post-processing solutions of immersed layer PDEs_

| Documentation | Build Status |
|:---:|:---:|
| [![Stable](https://img.shields.io/badge/docs-stable-blue.svg)](https://JuliaIBPM.github.io/ILMPostProcessing.jl/stable) [![Dev](https://img.shields.io/badge/docs-dev-blue.svg)](https://JuliaIBPM.github.io/ILMPostProcessing.jl/dev) | [![Build Status](https://github.com/JuliaIBPM/ILMPostProcessing.jl/workflows/CI/badge.svg)](https://github.com/JuliaIBPM/ILMPostProcessing.jl/actions) [![Coverage](https://codecov.io/gh/JuliaIBPM/ILMPostProcessing.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/JuliaIBPM/ILMPostProcessing.jl) |


This package contains tools that can be used to post-process and analyze the solutions of partial differential equations computed with the [ImmersedLayers.jl](https://github.com/JuliaIBPM/ImmersedLayers.jl) package. Currently implemented methods are
* flow lines (pathlines, streamlines, streaklines)
* proper orthogonal decomposition (POD)
* dynamic mode decomposition (DMD)
* finite-time Lyapunov exponent (FTLE)
* Lagrangian-averaged vorticity deviation (LAVD)

The examples in the documentation, which have companion notebooks in the `examples` folder, are the best way to get started.   
