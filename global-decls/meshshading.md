---
layout: stdlib-reference
---
# Mesh shading

This category contains the following declarations:

#### [DispatchMesh\<P\>](dispatchmesh-08.md)

#### [SetMeshOutputCounts](setmeshoutputcounts-037d.md)


```{toctree}
:titlesonly:
:hidden:

DispatchMesh <dispatchmesh-08>
SetMeshOutputCounts <setmeshoutputcounts-037d>
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
