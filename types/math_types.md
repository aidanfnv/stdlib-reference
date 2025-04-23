---
layout: stdlib-reference
---
# Math types

This category contains the following declarations:

#### [matrix\<T, R:int, C:int, L:int\>](matrix/index.md)

#### [vector\<T, N:int\>](vector/index.md)


```{toctree}
:titlesonly:
:hidden:

matrix <../types/matrix/index>
vector <../types/vector/index>
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
