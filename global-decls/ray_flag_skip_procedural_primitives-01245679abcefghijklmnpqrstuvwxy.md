---
layout: stdlib-reference
---

# RAY_FLAG_SKIP_PROCEDURAL_PRIMITIVES

## Description

Skips all procedural primitive intersections.


## Signature
<pre>
<span class='code_keyword'>static</span> <span class='code_keyword'>const</span> <span class="code_keyword">uint</span> <a href="ray_flag_skip_procedural_primitives-01245679abcefghijklmnpqrstuvwxy.md" class="code_var">RAY_FLAG_SKIP_PROCEDURAL_PRIMITIVES</a> = 0x200;
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
