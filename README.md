#   Matlab Finite Element routines for simple sheet pile walls (confined flow)

This is a set of Matlab routines for a 2D FEA of the flux at a sheet pile wall.

The files Sheet_Pile_Wall_1material.m and Sheet_Pile_Wall_3layers.m contain the code to solve the hydraulic problem.
Element used: Tri3 (CST, for flow).
Assembly routines are coded as functions.
The mesh generation is done using mesh2d, a Delaunay-based unstructured mesh generator (see https://ch.mathworks.com/matlabcentral/fileexchange/25555-mesh2d-delaunay-based-unstructured-mesh-generation for detailed information). This folder may has to be added to the path.

ProjectElementFlux.m and ProjectFlux.m are used to estimate the flux at the nodes.

The set of routines may be extended to 2D plane strain odr axi-symmetric FEA of laplacian, diffusion, elastic & coupled problems.

These files are part of the course CIVIL-423 'Computational Geomechanics' and should be regarded as such. Information on licencing (GNU-GPL) is given in the LICENCE file. Credits go to the author Brice Lecampion and his PhD-students at EPFL.

