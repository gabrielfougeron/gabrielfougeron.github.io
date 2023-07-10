---
title: "Contribution to the improvement of meshless methods applied to continuum mechanics"
collection: publications
permalink: /publications/fougeron2018phdthesis
description: 'My Ph. D. thesis.'
abstract: 'This thesis introduces a general framework for the study of nodal meshless discretization schemes. Its fundamental objects are the discrete operators defined on a point cloud : volume and boundary integration, discrete gradient and reconstruction operator. These definitions endow the point cloud with a weaker structure than that defined by a mesh, but share several fundamental concepts with it, the most important of them being integration-differentiation compatibility. Along with linear consistency of the discrete gradient, this discrete analogue of Stokes’s formula is a necessary condition to the linear consistency of weakly discretized elliptic operators. Its satisfaction, at least in an approximate fashion, yields optimally convergent discretizations. However, building compatible discrete operators is so difficult that we conjecture – without managing to prove it – that it either requires to solve a global linear system, or to build a mesh. We dub this conjecture the "meshless curse". Three main approaches for the construction of discrete meshless operators are studied. Firstly, we propose a correction method seeking the closest compatible gradient – in the least squares sense – that does not hurt linear consistency. In the special case of MLS gradients, we show that the corrected gradient is globally optimal. Secondly, we adapt the SFEM approach to our meshless framework and notice that it defines first order consistent compatible operators. We propose a discrete integration method exploiting the topological relation between cells and faces of a mesh preserving these characteristics. Thirdly, we show that it is possible to generate each of the meshless operators from a nodal discrete volume integration formula. This is made possible with the exploitation of the functional dependency of nodal volume weights with respect to node positions, the continuous underlying space and the total number of nodes. Consistency of the operators is characterized in terms of the initial volume weights, effectively constituting guidelines for the design of proper integration formulae. In this framework, we re-interpret the classical stabilization methods of the SPH community as actually seeking to cancel the error on the discrete version of Stokes’s formula. The example of SFEM operators has a volume-based equivalent, and so does its discrete mesh-based integration. Actually computing it requires a very precise description of the geometry of cells of the mesh, in particular in the case where its faces are not planar. We thus fully characterize the shape of such cells, only as a function of nodes of the mesh and topological relations between cells, allowing unambiguous definition of their volumes and centroids. Finally, we describe meshless discretization schemes of elliptic partial differential equations. We propose several alternatives for the treatment of boundary conditions with the concern of imposing as few constraints on nodes of the point cloud as possible. We give numerical results confirming the crucial importance of verifying the compatibility conditions, at least in an approximate fashion. This simple guideline systematically allows the recovery of optimal convergence rates of the studied discretizations.'
date: 2018-10-02
venue: 'Université Paris-Saclay'
paperurl: 'https://tel.archives-ouvertes.fr/tel-01968070'
citation: 'Fougeron, G. (2018). Contribution to the improvement of meshless methods applied to continuum mechanics. Doctoral dissertation, Université Paris-Saclay (ComUE).'
bibtex: "@phdthesis{fougeron2018phdthesis,
title = {{Contribution to the improvement of meshless methods applied to continuum mechanics}},
author = {Fougeron, Gabriel},
url = {https://tel.archives-ouvertes.fr/tel-01968070},
number = {2018SACLC068},
school = {{Université Paris-Saclay}},
year = {2018},
month = Oct,
keywords = {SPH ; Continuum Mechanics ; Simulation ; Meshless ; SPH ; Mécanique des milieux continus ; Simulation ; Sans-Maillage},
type = {Theses},
pdf = {https://tel.archives-ouvertes.fr/tel-01968070/file/74303_FOUGERON_2018_archivage.pdf},
HAL_ID = {tel-01968070},
HAL_VERSION = {v1}}"
---