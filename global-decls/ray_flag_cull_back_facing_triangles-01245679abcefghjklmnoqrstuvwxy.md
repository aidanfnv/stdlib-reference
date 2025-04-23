---
layout: stdlib-reference
---

# RAY_FLAG_CULL_BACK_FACING_TRIANGLES

## Description

Culls triangles facing away from the ray origin.


## Signature
<pre>
<span class='code_keyword'>static</span> <span class='code_keyword'>const</span> <span class="code_keyword">uint</span> <a href="ray_flag_cull_back_facing_triangles-01245679abcefghjklmnoqrstuvwxy.md" class="code_var">RAY_FLAG_CULL_BACK_FACING_TRIANGLES</a> = 0x10;
</pre>


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
