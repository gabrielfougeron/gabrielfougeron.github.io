---
title: "Finite Transformation Rigid Motion Mesh Morpher"
collection: publications
permalink: /publications/liatsikouras2019finite
description:
abstract: 'In any optimization framework, a robust and reliable mesh morpher is necessary to undertake the adaptation of the CFD mesh to the updated boundaries at each optimization cycle. Morphing has its share of challenges, namely to maintain high mesh quality (avoid distorted elements and tangles) even during extreme deformations. In this work, the Finite Transformation Rigid Motion Mesh Morpher (FT–R3M) is presented, an improved version of the Rigid Motion Mesh Morpher (Eleftheriou and Pierrot in Rigid motion mesh morpher: a novel approach for mesh deformation, 2016), that eliminates the need for sub-cycling, making it more efficient in terms of CPU time. FT–R3M, which bears some similarities to Chal et al. (ACM Trans Graph 29(4):38, 2010), is a mesh–less mesh morphing tool, since it does not require any inertial quantities, that gracefully propagates the movement of the boundaries (surface mesh) to the internal nodes of the mesh (volume mesh), by keeping the motion of its parts (referred to as stencils) as–rigid–as–possible. It is an optimization–based method, which means that the interior nodes of the computational mesh are displaced to minimize a distortion metric, namely the deformation energy. Since FT–R3M is minimizing the deformation energy between the initial and the final configuration, as opposed to R3M, in which the deformation energy is minimized from each sub-cycle to another, there is a significant gain in terms of the quality of the resulting mesh. The efficiency of the morpher proposed in this article will be demonstrated in small and medium–size cases.'
date: 2018-09-07
venue: ' Computational Methods in Applied Sciences'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-319-89890-2_7'
citation: 'Liatsikouras, A. G., Pierrot, G., Fougeron, G., & Eleftheriou, G. S. (2019). Finite transformation rigid motion mesh morpher. In Evolutionary and Deterministic Methods for Design Optimization and Control With Applications to Industrial and Societal Problems (pp. 93-107). Springer, Cham.'
bibtex: '@incollection{liatsikouras2019finite,
title={Finite transformation rigid motion mesh morpher},
author={Liatsikouras, Athanasios G and Pierrot, Guillaume and Fougeron, Gabriel and Eleftheriou, George S},
booktitle={Evolutionary and Deterministic Methods for Design Optimization and Control With Applications to Industrial and Societal Problems},
pages={93--107},
year={2019},
publisher={Springer}
}'
---






