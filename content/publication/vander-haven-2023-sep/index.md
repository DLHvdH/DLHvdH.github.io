---
title: A physically consistent Discrete Element Method for arbitrary shapes using Volume-interacting Level Sets
authors:
- admin
- Ioannis S. Fragkopoulos
- James A. Elliott
date: '2023-09-01'
publishDate: '2025-01-26T18:17:07.811477Z'
publication_types:
- article-journal
publication: '*Comput. Methods Appl. Mech. Eng.*'
doi: 10.1016/j.cma.2023.116165

abstract: The properties of granular materials depend strongly on the shapes of their individual constituent particles or granules. Nonetheless, incorporating the effects of non-spherical or complex particle shapes into existing modelling frameworks, such as the discrete element method (DEM), has remained challenging. In this work, we propose the volume-interaction level set DEM (VLS-DEM) approach for carrying out physically accurate simulations of particles with arbitrary geometries. VLS-DEM builds upon level set DEM (LS-DEM), both of which implicitly define the geometry of a particle through a discrete signed distance function. However, instead of using surface nodes to compute the interparticle forces, VLS-DEM uses the overlap volume as computed by an Octree integration algorithm. This addresses some of the shortcomings of LS-DEM in terms of the accuracy and precision of the shape description and opens up the possibility for bottom-up parametrisation methods. A number of tests were performed to compare VLS-DEM with regular DEM, LS-DEM, and analytical models. VLS-DEM is shown to give physically accurate results, comparable to analytical theory, even for highly complex systems such as those with concave interlocked particles.

summary: A new variant of the discrete element method (DEM) with extensive testing, working on highly complex shapes such as those that are concave and interlocking.

tags:
  - Discrete Element Method
  - Level Set / Signed Distance Function

# Display this page in the Featured widget?
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Used under CC BY 4.0.'
  focal_point: ''
  preview_only: false
---
