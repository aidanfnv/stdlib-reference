---
layout: stdlib-reference
---

# enum CoopMatMatrixUse

## Values 

####  <a id="decl-MatrixA"></a>_MatrixA = 0_
####  <a id="decl-MatrixB"></a>_MatrixB = 1_
####  <a id="decl-MatrixAccumulator"></a>_MatrixAccumulator = 2_

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
