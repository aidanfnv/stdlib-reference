---
layout: stdlib-reference
---

# struct OutputVertices\<T, MAX\_VERTS:uint\>

## Description



## Generic Parameters

####  <a id="typeparam-T"></a>T
####  <a id="decl-MAX_VERTS"></a>MAX\_VERTS  : uint

## Methods

* [\_metalSetVertex](0metalsetvertex-069.md)
* [\_setVertex](0setvertex-04.md)
* [subscript](subscript.md)


```{toctree}
:titlesonly:
:hidden:

_metalSetVertex <../types/outputvertices-06/0metalsetvertex-069>
_setVertex <../types/outputvertices-06/0setvertex-04>
subscript <../types/outputvertices-06/subscript>
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
