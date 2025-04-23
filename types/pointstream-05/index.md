---
layout: stdlib-reference
---

# struct PointStream\<T\>

## Description



## Generic Parameters

####  <a id="typeparam-T"></a>T

## Methods

* [Append](append-0.md)
* [RestartStrip](restartstrip-07.md)


```{toctree}
:titlesonly:
:hidden:

Append <../types/pointstream-05/append-0>
RestartStrip <../types/pointstream-05/restartstrip-07>
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
