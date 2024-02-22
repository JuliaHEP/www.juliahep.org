+++
title = "Roadmap"
+++

# Roadmap for JuliaHEP

This is a loose collection of topics we, as the JuliaHEP working group, have an
eye on and want to organize community contributions as well as take action by
ourself.

## Interoperation with existing software

It is obvious that we want to support and/or establish interoperation with
exsisting HEP codes, especial (but not restricted to) those written in
C++. Examples are 

 * [ROOT](https://root.cern), 
 * [Minuit](https://root.cern.ch/download/minuit.pdf),
 * [FastJet](https://fastjet.fr), 
 * [Geant4](https://geant4.web.cern.ch), 
 * [Pythia8](https://pythia.org), 
 * other event generators,
 * etc.

Here the essential part is the possiblity to read from/write to common file formats
using common data structures (e.g. [RNTuple](https://root.cern.ch/doc/v618/md_tree_ntuple_v7_doc_README.html), see below). Furthermore, we
eventually want to automate the generation of wrappers/bindings as far as possible to keep the
maintenance efford small. This should be established by [Wrapit](https://github.com/grasph/wrapit) and [CxxWrap.jl](https://github.com/JuliaInterop/CxxWrap.jl),
where we therefore support needed enhancements and developments. 

## Software packages for HEP-data analysis
We want to monitor and support the plain Julia implementations of software
packages dedicated to HEP-data analysis. This includes reading data files from 
various data standards and file-formats, e.g. [HEPMC3](https://gitlab.cern.ch/hepmc/HepMC3), LHEF (see [LHEF.jl](https://github.com/JuliaHEP/LHEF.jl)), ROOT histograms (at least top level), [Boost.Histogram](https://www.boost.org/doc/libs/1_84_0/libs/histogram/doc/html/index.html), and others.
For writing to files, we want to support the implementations for ROOT files, at least based
on [RNTuple](https://root.cern.ch/doc/v618/md_tree_ntuple_v7_doc_README.html).
Finally, we want to support and establish upcoming statistical data
standards, namely [HS3](https://github.com/hep-statistics-serialization-standard/hep-statistics-serialization-standard).

## General JuliaHEP libraries and interfaces
In addition to the data-analysis related software packages, we want to support
and provide general libraries and interfaces for various HEP-tasks. This
includes the general treatment of Euclidian and Lorentz vectors, similar but not limited to the functionality in [Scikit-hep/vector](https://github.com/scikit-hep/vector) and [`ROOT::Math::LorentzVector`](https://root.cern/doc/master/classROOT_1_1Math_1_1LorentzVector.html).
Futhermore, we support libraries, which provide access to HEP-related physical 
constants (e.g. [`PhysicalConstants.jl`](https://github.com/JuliaPhysics/PhysicalConstants.jl)), 
and particle data (e.g. [`Corpuscles.jl`](https://github.com/JuliaPhysics/Corpuscles.jl) and [`PDGdb.jl`](https://github.com/mmikhasenko/PDGdb.jl)).
Last, but not least, we want to support and establish recipes and
functionalities for various plotting packages,
e.g. [`Makie.jl`](https://docs.makie.org/stable/) and
[`Plots.jl`](`https://docs.juliaplots.org/stable/`) (most probably via [`Plots.RecipesBase`](https://github.com/JuliaPlots/Plots.jl/tree/master/RecipesBase)).

## Machine-learing in HEP
We want to support the development of HEP-related applications of Julia's
machine-leaning eco-system, e.g. using [`Flux.jl`](https://github.com/FluxML/Flux.jl) or [`MLJ.jl`](https://github.com/alan-turing-institute/MLJ.jl).
Especially developments towards differentable physics simulations (see, e.g. [`Zygote.jl`](https://github.com/FluxML/Zygote.jl)) 
are supported as a conceivable approach for parameter optimization. 
Futhermore, the usage of normalizing flows and other generative models are
supported, e.g. for Baysian analysis and Monte-Carlo event generation.
Finally, we want to collect and establish HEP-dedicated ML-training material, e.g. in the form of expressive
examples and tutorials. 

## High-performance computing in HEP
* trainig 
* discussion of needed tooling
* GPU-support

## Workflow tooling
* snakemake equivalient (really needed?)
* is there an equivalent for xyzpy?

## Documentation and training

