# hep
simulator for particle detector

To run:
1. source geant4[...]-build/geant4make.sh
2. in B4b-build, ./exampleB4b.

TODO:
Remove the other basic examples, add gitignore for compiled files.

Notes:
If the visualization macro is causing trouble, make sure that you are running from the same directory as the macros

make command: cmake -DGeant4_DIR=~/Phys/geant4.10.04 ../B4b
to run, must source geant4: source ~/Phys/geant4.10.04-build/geant4make.sh
