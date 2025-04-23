---
layout: stdlib-reference
---

# enum CoopVecMatrixLayout

## Description

Specifies the memory layout for matrices used in cooperative vector operations.

## Values 

####  <a id="decl-RowMajor"></a>_RowMajor = _
####  <a id="decl-ColumnMajor"></a>_ColumnMajor = _
####  <a id="decl-InferencingOptimal"></a>_InferencingOptimal = _
####  <a id="decl-TrainingOptimal"></a>_TrainingOptimal = _
## Remarks

This enum defines different matrix layout options that affect how matrix data is stored and accessed,
including standard row-major and column-major layouts as well as specialized layouts optimized for specific operations.



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
