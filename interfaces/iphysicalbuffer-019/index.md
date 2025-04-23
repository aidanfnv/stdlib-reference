---
layout: stdlib-reference
---

# interface IPhysicalBuffer

## Methods

* [LoadByteOffset](loadbyteoffset-048.md)
* [GetBufferPointer](getbufferpointer-039.md)


```{toctree}
:titlesonly:
:hidden:

GetBufferPointer <../interfaces/iphysicalbuffer-019/getbufferpointer-039>
LoadByteOffset <../interfaces/iphysicalbuffer-019/loadbyteoffset-048>
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
