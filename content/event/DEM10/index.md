---
title: Branched Coupling of Representative Volume Elements; fast hierarchical FEM-DEM simulations
event: DEM10 - 10th International Conference on Discrete Element Methods
event_url: https://www.sptj.jp/dem10/

location: Japan
address:
  street: 143-2 Kamiyacho
  city: Himeji
  region: Hyogo
  postcode: '670-0836'
  country: Japan

summary: I presented at this conference.
abstract: 'The large-scale mechanical behaviour of granular materials remains difficult to predict and simulate because of the lack of a sufficiently accurate or complete constitutive model. As a result, hierarchical coupling methods have been developed in which e.g. the finite element method (FEM) gets the material response from a smaller scale discrete element method (DEM) simulation instead of a constitutive model. In this work, we investigate the development of a new hierarchical FEM-DEM method with direct coupling using a reduced number of representative volume elements (RVEs). Although the original hierarchical FEM-DEM method has been hugely successful in predicting e.g. shear banding, it naturally comes with a very high computational cost since each Gauss point of the FEM simulation is assigned a unique RVE and thereby requires just as many DEM simulations. To reduce the computational cost, others have moved away from direct coupling and used an indirect data-driven coupling with e.g. physically informed neural networks (PINNs). Although this significantly reduces the runtime of the simulations, data-driven approaches come with a high upfront training cost. This work instead makes use of the realisation that many RVEs have highly similar strain states, thus meaning that a single DEM simulation can inform the stress response at multiple Gauss points. By applying clustering methods, Gauss points are automatically grouped and regrouped during the simulation to maintain both accuracy and efficiency. The new FEM-DEM coupling method is significantly faster than the original and has no a priori training cost.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-07-03T13:00:00Z'
date_end: '2025-07-05T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**DEM10**](https://www.sptj.jp/dem10/)'
  focal_point: Right


---

