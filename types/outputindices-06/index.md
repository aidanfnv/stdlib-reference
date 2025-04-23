---
layout: stdlib-reference
---

# struct OutputIndices\<T, MAX\_PRIMITIVES:uint\>

## Description



## Generic Parameters

####  <a id="typeparam-T"></a>T
####  <a id="decl-MAX_PRIMITIVES"></a>MAX\_PRIMITIVES  : uint

## Methods

* [subscript](subscript.md)


```{toctree}
:titlesonly:
:hidden:

subscript <../types/outputindices-06/subscript>
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
