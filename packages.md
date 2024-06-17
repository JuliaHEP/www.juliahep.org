+++
title = "Packages"
+++

# ROOT file and event-loop based workflow
- [ROOT.jl](https://github.com/JuliaHEP/ROOT.jl) wraps a selected number of classes from [ROOT](https://root.cern) 
- Reading ROOT files (TTree/RNTuple): [UnROOT.jl](https://github.com/JuliaHEP/UnROOT.jl)
- Histogramming: [FHist.jl](https://github.com/Moelf/FHist.jl) ([example
  plots](https://moelf.github.io/FHist.jl/dev/notebooks/makie_plotting/))
- Analysis Grand Challenge example: [LHC_AGC.jl](https://github.com/Moelf/LHC_AGC.jl)
- [EDM4hep.jl](https://github.com/peremato/EDM4hep.jl) Prototype of 
  the [EDM4hep](https://github.com/key4hep/EDM4hep) (generic Event Data Model for HEP experiments part of [Key4hep]()) for Julia. Read access to ROOT files with EDM4hep data.
  the [EDM4hep](https://github.com/key4hep/EDM4hep) (generic Event Data Model for HEP experiments part of [Key4hep](https://key4hep.github.io/key4hep-doc/index.html)) for Julia. Read access to ROOT files with EDM4hep data.


# Simulation
- [Geant4.jl](https://github.com/JuliaHEP/Geant4.jl) wraps the major user 
  interface classes of the [Geant4](https://geant4.web.cern.ch) simulation toolkit. It allows to develop detector simulation
  applications with Julia. Example applications are hosted in a separate package [G4Examples.jl](https://github.com/JuliaHEP/G4Examples.jl).
  A jupyter book with tutorials is available at [Geant4.jl-tutorial](https://github.com/peremato/Geant4.jl-tutorial)

# Reconstruction
- [JetReconstruction.jl](https://github.com/JuliaHEP/JetReconstruction.jl) Set of algorithms for jet clustering based on the C++ [FastJet](https://fastjet.fr) package.

# Data access
- [XRootD.jl](https://github.com/JuliaHEP/XRootD.jl) wraps the client functionality of [XRootD](https://xrootd.slac.stanford.edu),
  which is high performance, scalable, and fault tolerant access to data repositories