---
title: "Level-Set Particle And Geometry GEnerator (LS-PAGGE): Accurate representations of arbitrary particle shapes"
authors:
- admin
- Philipp Kloza
- Ioannis S. Fragkopoulos
- James A. Elliott
date: '2026-01-10'
publishDate: '2026-01-10T18:17:07.781612Z'
publication_types:
- article-journal
publication: '*Powder Technology*'
doi: /10.1016/j.powtec.2026.122134

abstract: Discrete level sets (LS), also known as signed distance functions (SDF), are able to provide highly detailed descriptions of arbitrary geometries, including concave and interlocking shapes, at a relatively low computational cost compared to other shape representations. Level sets have therefore become a popular method to describe geometries in both computational fluid dynamics (CFD) and discrete element method (DEM) simulations. However, the construction of an appropriate level set can be difficult, especially if the geometries are supplied in different formats (e.g. mesh, voxel image, etc.) or need to be modified. This creates a high entry barrier and limits the more widespread usage of level-set methods. Here, a new reinitialisation algorithm is proposed to determine the distance values close to the interface of the object, allowing the generation of an appropriate level set for any geometry. Furthermore, we present a method for determining and adjusting the maximum curvature of the object and a method for adaptively generating meshes and surface nodes to improve the accuracy of contact interactions. All of these developments are included in LS-PAGGE; a new open-code MATLAB package for creating level-set representations from images, meshes, clumps, and user-defined functions. LS-PAGGE can modify level sets using a multitude of operations that allow, e.g., the rotation, merging, splitting, and simplification of particles or objects. The final level-set geometry can be directly exported for DEM/CFD simulations or as a voxel image, mesh, or clump.

summary: This paper presents a software package for creating signed distance functions of any object or shape from e.g. images or STL files.

tags:
  - Level Set / Signed Distance Function
  - Discrete Element Method
  - Open Source

# Display this page in the Featured widget?
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Used under CC BY 4.0.'
  focal_point: ''
  preview_only: false

---
