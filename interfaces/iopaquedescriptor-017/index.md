---
layout: stdlib-reference
---

# interface IOpaqueDescriptor

## Description

Represents an opaque descriptor type, such as textures, samplers, and buffers etc,
whose size may be undefined and can't be directly accessed as ordinary data.


## Fields

####  <a id="decl-kind"></a>[kind](kind.md) : [DescriptorKind](../../types/descriptorkind-0a/index.md)
The kind of the descriptor.



```{toctree}
:titlesonly:
:hidden:

kind <../interfaces/iopaquedescriptor-017/kind>
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
