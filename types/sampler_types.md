---
layout: stdlib-reference
---
# Sampler types

This category contains the following declarations:

#### [SamplerComparisonState](samplercomparisonstate-07h/index.md)

#### [SamplerState](samplerstate-07/index.md)


```{toctree}
:titlesonly:
:hidden:

SamplerComparisonState <../types/samplercomparisonstate-07h/index>
SamplerState <../types/samplerstate-07/index>
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
