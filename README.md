# Geant4 2025  Beam-test MID simulation 

This is the code for a simulation in Geant4 for the experimental setup of the MID of the beam test done by the ALICE-BUAP team in 2025. The thickness of the steel absorber was changed
between 64 cm, 74 cm, and 84 cm. You can change it in DetectorConstruction.cc. The distance between the absorber and the first scintillators layer must keep the same (the layer one with the bar's numbers between 10 and 19). 

By the other hand, the particle beam (mu+ and pi+) has a trajectory disperssion based in a Poisson distribution, where the sigma values for the X and Y coordinates (in the simulation system, X and Z)
changed according to the momentum of the beam. You can change it in the PrimaryGeneraatorAction.cc.

*This simulation was created by MC Leonardo Fernandez. Puebla, Mexico.*

