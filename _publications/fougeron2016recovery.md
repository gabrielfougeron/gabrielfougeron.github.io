---
title: "Recovery of differentiation/integration compatibility of meshless operators via local adaptation of the point cloud in the context of nodal integration"
collection: publications
permalink: /publications/fougeron2016recovery
description:
abstract: "Standard SPH methods are very attractive to simulate complex flow problems thanks to their robustness and ease of implementation, but often suffer from poor precision regarding point-wise stress computation or stability issues characterized by a loss of quality of the point cloud (particle clumping, formation of voids). In this paper, we recall an operator-based framework for the description of meshless discretizations using nodal integration. Using this framework, we are able to define a dual gradient inspired by the integration by parts formula, clarify its role in the discretization of a simple diffusion problem and specify sufficient conditions to satisfy the patch test. For symmetric discretizations, we show that one of these conditions reduces to a discrete version of Stokes' theorem, which we call differentiation/integration compatibility of meshless operators. Our earlier work focused on the recovery of these compatibility conditions via the modification of gradient coefficients. In a companion presentation, we extend the analysis to the concept of element-based integration and investigate the possibility of a one-shot solution algorithm, jointly solving for both compatibility and pressure. The present work however is an attempt at achieving compatibility while keeping the computational simplicity of SPH. Instead of solving a global linear system for compatibility, the position of SPH nodes are adapted so that compatibility conditions are naturally enforced using classical and well-known SPH gradients. In the context of Lagrangian simulation, this means that the SPH nodes are not advected with the physical velocity, but with a corrected velocity. The idea is not new: it can be traced back to Monaghan and his XSPH formulation, and appeared more recently in the context of fluid dynamics with the works of Adami, Hu and Adams. In this work, we try to incorporate their corrections to our framework, generalize their method and give a novel interpretation for their results."
date: 2016-06-05
venue: 'Proceedings of the VII European Congress on Computational Methods in Applied Sciences and Engineering'
paperurl: 'https://www.eccomasproceedia.org/conferences/eccomas-congresses/eccomas-congress-2016/1837'
citation: 'Fougeron, G., Pierrot, G., & Aubry, D. (2016, June). Recovery of differentiation/integration compatibility of meshless operators via local adaptation of the point cloud in the context of nodal integration. In VII European Congress on Computational Methods in Applied Sciences and Engineering.'
bibtex: '@article{fougeron2016recovery,
title = {Recovery of differentiation/integration compatibility of meshless operators via local adaptation of the point cloud in the context of nodal integration},
journal = {ECCOMAS Congress 2016 - Proceedings of the 7th European Congress on Computational Methods in Applied Sciences and Engineering},
year = {2016},
volume = {1},
pages = {568-585},
author = {Fougeron, G. and Pierrot,  G. and Aubry, D.}}'
---
