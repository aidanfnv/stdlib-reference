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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
