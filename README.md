This notebook is part of the CoMPLEX MRes mini-project: Modelling the self-assembly of COPII outer coat (http://www.ucl.ac.uk/~ucbpfgo/img/MP1.pdf). The code simulates Sec13-31 rods of COPII outer coat. The first 2 sections of the notebook define Sec13-31 subunits and their assembly into cuboctahedral cages observed during in-vitro experiments. The last part of the notebook was written to automatically place 3d rods in a limitted space avoiding their overlapping. As an output, the code provides the coordinates of a priori defined rods. These coordinates were used as an input for LAMMPS (https://lammps.sandia.gov/) to perform molecular dynamic simulations. 

Most of this code can be addapted to place non-overlapping objects in 3D space, define different object shapes, the space dimensions, and the minimum distance between objects. The objects are placed in a random position within the 3D space and their orientation is randomly generated by applying a rotation matrix to each object. Note that the script was written using mathematica notebooks. 

