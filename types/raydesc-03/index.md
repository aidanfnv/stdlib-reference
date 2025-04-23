---
layout: stdlib-reference
---

# struct RayDesc

## Description

Describes a ray for traversal through an acceleration structure.


## Fields

####  <a id="decl-Direction"></a>[Direction](direction-0.html) : [vector](../vector/index.html)\<float, 3\>
Normalized direction vector of the ray in world space.

####  <a id="decl-Origin"></a>[Origin](origin-0.html) : [vector](../vector/index.html)\<float, 3\>
Starting point of the ray in world space.

####  <a id="decl-TMax"></a>[TMax](tmax-01.html) : float
Maximum distance along the ray to consider intersections.

####  <a id="decl-TMin"></a>[TMin](tmin-01.html) : float
Minimum distance along the ray to consider intersections.


## Methods

* init


```{toctree}
:titlesonly:
:hidden:

Direction <../types/raydesc-03/direction-0>
Origin <../types/raydesc-03/origin-0>
TMax <../types/raydesc-03/tmax-01>
TMin <../types/raydesc-03/tmin-01>
```
