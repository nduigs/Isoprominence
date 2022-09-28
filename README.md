# Isoprominence 

Investigations into the property of isoprominence for magnetic fields.

This project investigates the property of isoprominence for magnetic fields.
Isoprominent fields have been proven to mitigate sepatrix crossings of guiding centre orbits.
The project aims to theoretically and numerically investigate isoprominent fields.

## Near-Axis Expansion for Isoprominence

### Description

This part of the project uses Mathematica to generate a near-axis expansion of isoprominent magnetic fields.
Some examples are given.

### Prerequisites
* Mathematica 10.0+

### Description of files
* *IsoprominenceConditions.nb* - This Mathematica notebook generates the conditions for a magnetic field to be isoprominent in Frenet-Serret coordinates. Specify the parameter *order* and run the notebook to generate two files, *hsols_n.wdx* and *Bdiv0_n.wdx*, which give the isoprominent conditions to order n and the corresponding divergence-free magnetic field to order n, respectively.
* *NearAxisExamples.nb* - Requires *IsoprominenceConditions.nb* to have been run with order=3. This notebook generates two example isoprominent fields. 

### Issues
If you uncover any issues please use the [issue tracker](https://github.com/nduigs/Isoprominence/issues).

### Citation