---
layout: stdlib-reference
---

# struct RayDesc

## Description

Describes a ray for traversal through an acceleration structure.


## Fields

####  <a id="decl-Direction"></a>[Direction](direction-0.md) : [vector](../vector/index.md)\<float, 3\>
Normalized direction vector of the ray in world space.

####  <a id="decl-Origin"></a>[Origin](origin-0.md) : [vector](../vector/index.md)\<float, 3\>
Starting point of the ray in world space.

####  <a id="decl-TMax"></a>[TMax](tmax-01.md) : float
Maximum distance along the ray to consider intersections.

####  <a id="decl-TMin"></a>[TMin](tmin-01.md) : float
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

<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      const href = link.getAttribute('href');
      if (href && href.includes('.md')) {
        // This regex will handle .md links with or without fragment identifiers or query parameters
        link.href = link.href.replace(/(.+)\.md(#[^?]*)?(\?.*)?$/, '$1.html$2$3');
      }
    });
  });
}
</script>
