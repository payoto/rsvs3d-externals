# 3D-RSVS #
[![3D Restricted Snakes Volume of Solid Parameterisation](https://raw.githubusercontent.com/payoto/rsvs3d/master/SRCC/docs/3DRSVS_LR1.gif)](https://github.com/payoto/rsvs3d/releases)

The 3D-RSVS is a geometry generation tool using volume specification to build
smooth surfaces. Papers describing the method are available on 
[researchgate](https://www.researchgate.net/publication/330197375_Parametric_Surfaces_with_Volume_of_Solid_Control_for_Optimisation_of_Three_Dimensional_Aerodynamic_Topologies) 
and [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0045793018304730).


Last updated 12/11/2019
[Full documentation](https://payoto.github.io/rsvs3d_docs/)
available.

# What is this repository for? #

This repository contains the external dependencies of the [rsvs3d project](https://github.com/payoto/rsvs3d).

# Pre-requisites #

3rd party open source libraries in this repository:  

 + [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page): Library for linear algebra
   (templated, header only).
 + [boost/filesytem](https://www.boost.org/): Use some filesystem command for interface 
   (needs to be compiled).
 + [cxxopts](https://github.com/jarro2783/cxxopts/releases): Handling of command line arguments
   (header only).
 + [JSON for Modern C++](https://github.com/nlohmann/json/releases): JSON handling for c++. Used
   for the parameter handling of the RSVS3D framework (single include header).

# License #

Licenses for each project are included in each of the library directories.