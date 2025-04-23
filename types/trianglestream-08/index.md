---
layout: stdlib-reference
---

# struct TriangleStream\<T\>

## Description



## Generic Parameters

####  <a id="typeparam-T"></a>T

## Methods

* [Append](append-0.md)
* [RestartStrip](restartstrip-07.md)


```{toctree}
:titlesonly:
:hidden:

Append <../types/trianglestream-08/append-0>
RestartStrip <../types/trianglestream-08/restartstrip-07>
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
