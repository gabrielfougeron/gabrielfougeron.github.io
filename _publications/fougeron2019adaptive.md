---
title: "An adaptive tree structure for the discrete integration of the weak forms arising in the meshless simulation of elliptic equations"
collection: publications
permalink: /publications/fougeron2019adaptive
description:
abstract: 'Since their introduction in the late 1970s, Lagrangian meshless methods like Smoothed Particle Hydrodynamics (SPH) have been advocated as ideally suited to simulate complex mechanical behaviors with large local deformations such as high velocity impacts, free surface flow, fluid-structure interaction, etc … These methods take advantage of the definition of self-reorganizing connectivities between discretization entities, in sharp contrast with the fixed structure imposed by a mesh.
However, several application cases (such as the tension instability phenomenon identified by Swegle et al) have revealed serious weaknesses in the predictive power of SPH. Most troubling, the accuracy of the stress tensor in quasi-static to mildly dynamic simulations was found lacking. This phenomenon has been interpreted by Bonet and Kulasegaram and Babuška as the consequence of a fundamental mismatch between the evaluation of derivatives and numerical integration.
In an earlier work, we have shown that the introduction of a background integration mesh was enough to devise a proper integration procedure for the meshless weak form. The relative densities of the integration cells of the mesh and nodes of the point cloud was found to be a key parameter to achieve reasonable precision at the lowest computational cost. 
In this work, we propose a new method to adapt the size of the integration cells to the local density of the point cloud. This method takes full advantage of the independence of the background integration mesh with respect to the point cloud with the introduction of an adaptive tree-like structure controlling the integration. A general refinement algorithm is proposed and different heuristics are compared. Simulation results are given on a linear elastic cracked geometry under tensile loading.
'
date: 2019-06-18
venue: 'Proceedings of the 2019 NAFEMS World Congress'
paperurl: 'https://www.nafems.org/publications/resource_center/nwc_19_220/'
citation: 'Fougeron, G.,  Kamoulakos, A. (2019, June). An adaptive tree structure for the discrete integration of the weak forms arising in the meshless simulation of elliptic equations. In Proceedings of the 2019 NAFEMS World Congress.'
bibtex: '@article{fougeron2019adaptive,
title = {An adaptive tree structure for the discrete integration of the weak forms arising in the meshless simulation of elliptic equations},
journal = {Proceedings of the 2019 NAFEMS World Congress},
year = {2019},
author = {Fougeron, G. and Kamoulakos, A.}}'
---
