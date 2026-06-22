# Geant4 2025  Beam-test MID simulation 

This is the code for a simulation in Geant4 for the experimental setupof the MID of the beam test done by the ALICE-BUAP team in 2025. The thickness of the steel absorber was changed
between 64 cm, 74 cm, and 84 cm. You can change it in DetectorConstruction.cc. The distance between the absorber and the first scintillators layers must keep the same. 

By the other hand, the particle beam (mu+ and pi+) has a possion disperssion where the sigma values for the X and Y coordinates (in the simulation system, X and Z)
changed according to the momentum of the beam. You can change it in the PrimaryGeneraatorAction.cc.

*This simulation was created by MC Leonardo Fernandez. Puebla, Mexico.*

