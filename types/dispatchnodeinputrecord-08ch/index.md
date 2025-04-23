---
layout: stdlib-reference
---

# struct DispatchNodeInputRecord\<T\>

## Description

read-only input to Broadcasting launch node.


## Generic Parameters

####  <a id="typeparam-T"></a>T

## Methods

* [Get](get-0.md)


```{toctree}
:titlesonly:
:hidden:

Get <../types/dispatchnodeinputrecord-08ch/get-0>
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
