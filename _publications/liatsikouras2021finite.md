---
title: "Finite transformation rigid motion mesh morpher; A grid deformation approach"
collection: publications
permalink: /publications/liatsikouras2021finite
description:
abstract: 'In any shape optimization framework and specifically in the context of computational fluid dynamics, a robust and reliable grid deformation tool is necessary to undertake the adaptation of the computational mesh to the updated boundaries at each optimization cycle. Grid deformation has its share of challenges, namely, to maintain high mesh quality (avoid distorted elements and tangles) even when dealing with extreme deformations. In this work a novel grid deformation algorithm, the finite transformation rigid motion mesh morpher (FT-R3M) is proposed. FT-R3M is essentially a mesh-free grid deformation approach, since it does not require any inertial quantities and it gracefully propagates the movement of the boundaries (surface mesh) to the internal nodes of the mesh (volume mesh), by keeping the motion of its parts (referred to as stencils) as-rigid-as-possible. It is an optimization-based method, which means that the interior nodes of the computational mesh are displaced to minimize a distortion metric related to the elastic deformation energy, by favoring rigidity in critical directions, thus being able to handle mesh anisotropies very efficiently. Results are presented for three test cases; a rotated airfoil with a mesh appropriate for viscous flow; a simulation of a low Reynolds duct case; a beam.'
date: 2020-08-31
venue: 'International Journal for Numerical Methods in Fluids'
paperurl: 'https://onlinelibrary.wiley.com/doi/abs/10.1002/fld.4912'
citation: 'Liatsikouras, A. G., Fougeron, G., Eleftheriou, G. S., & Pierrot, G. (2021). Finite transformation rigid motion mesh morpher; A grid deformation approach. International Journal for Numerical Methods in Fluids, 93(3), 874-891.'
bibtex: '@article{liatsikouras2021finite,
title={Finite transformation rigid motion mesh morpher; A grid deformation approach},
author={Liatsikouras, Athanasios G and Fougeron, Gabriel and Eleftheriou, George S and Pierrot, Guillaume},
journal={International Journal for Numerical Methods in Fluids},
volume={93},
number={3},
pages={874--891},
year={2021},
publisher={Wiley Online Library}}'
---


