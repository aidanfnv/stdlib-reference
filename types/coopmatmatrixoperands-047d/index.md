---
layout: stdlib-reference
---

# enum CoopMatMatrixOperands

## Values 

####  <a id="decl-None"></a>_None = 0x0_
####  <a id="decl-MatrixASigned"></a>_MatrixASigned = 0x1_
####  <a id="decl-MatrixBSigned"></a>_MatrixBSigned = 0x2_
####  <a id="decl-MatrixCSigned"></a>_MatrixCSigned = 0x4_
####  <a id="decl-MatrixResultSigned"></a>_MatrixResultSigned = 0x8_
####  <a id="decl-SaturatingAccumulation"></a>_SaturatingAccumulation = 0x10_

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
