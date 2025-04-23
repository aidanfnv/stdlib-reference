---
layout: stdlib-reference
---

# struct BuiltInTriangleIntersectionAttributes

## Description

Built-in structure containing intersection attributes for triangle primitives.


## Fields

####  <a id="decl-barycentrics"></a>[barycentrics](barycentrics.md) : [vector](../vector/index.md)\<float, 2\>
Barycentric coordinates of the intersection point on the triangle.


## Methods

* init


```{toctree}
:titlesonly:
:hidden:

barycentrics <../types/builtintriangleintersectionattributes-057fr/barycentrics>
```

<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
