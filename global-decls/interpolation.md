---
layout: stdlib-reference
---
# Vertex Interpolation Functions

This category contains the following declarations:

#### [EvaluateAttributeAtCentroid\<T\>](evaluateattributeatcentroid-08hj.md)

#### [EvaluateAttributeAtSample\<T\>](evaluateattributeatsample-08hj.md)

#### [EvaluateAttributeSnapped\<T\>](evaluateattributesnapped-08h.md)


```{toctree}
:titlesonly:
:hidden:

EvaluateAttributeAtCentroid <evaluateattributeatcentroid-08hj>
EvaluateAttributeAtSample <evaluateattributeatsample-08hj>
EvaluateAttributeSnapped <evaluateattributesnapped-08h>
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
