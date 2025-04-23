---
layout: stdlib-reference
---
# Bit operation functions

This category contains the following declarations:

#### [countbits\<T\>](countbits.md)

#### [firstbithigh](firstbithigh.md)

#### [firstbitlow](firstbitlow.md)

#### [reversebits](reversebits.md)


```{toctree}
:titlesonly:
:hidden:

countbits <countbits>
firstbithigh <firstbithigh>
firstbitlow <firstbitlow>
reversebits <reversebits>
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
