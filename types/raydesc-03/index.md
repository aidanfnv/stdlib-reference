---
layout: stdlib-reference
---

# struct RayDesc

## Description

Describes a ray for traversal through an acceleration structure.


## Fields

####  <a id="decl-Direction"></a>[Direction]() : [vector](../types/vector/index)\<float, 3\>
Normalized direction vector of the ray in world space.

####  <a id="decl-Origin"></a>[Origin]() : [vector](../types/vector/index)\<float, 3\>
Starting point of the ray in world space.

####  <a id="decl-TMax"></a>[TMax]() : float
Maximum distance along the ray to consider intersections.

####  <a id="decl-TMin"></a>[TMin]() : float
Minimum distance along the ray to consider intersections.


## Methods

* init


```{toctree}
:titlesonly:
:hidden:

Direction <direction-0>
Origin <origin-0>
TMax <tmax-01>
TMin <tmin-01>
```
