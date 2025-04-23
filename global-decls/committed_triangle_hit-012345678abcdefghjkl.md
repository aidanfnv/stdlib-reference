---
layout: stdlib-reference
---

# COMMITTED_TRIANGLE_HIT

## Description

Closest hit is a triangle.
This could be an opaque triangle hit found by the fixed-function
traversal and intersection implementation, or a non-opaque
triangle hit committed by user code with <span class='code'><a href="../types/rayquery-03/index.md" class="code_type">RayQuery</a>.<a href="../types/rayquery-03/commitnonopaquetrianglehit-069fn.md">CommitNonOpaqueTriangleHit</a></span>.


## Signature
<pre>
<span class='code_keyword'>static</span> <span class='code_keyword'>const</span> <span class="code_keyword">uint</span> <a href="committed_triangle_hit-012345678abcdefghjkl.md" class="code_var">COMMITTED_TRIANGLE_HIT</a> = 1;
</pre>


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
