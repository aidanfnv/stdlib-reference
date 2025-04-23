---
layout: stdlib-reference
---

# RAY_FLAG_FORCE_NON_OPAQUE

## Description

Forces all geometries to be treated as non-opaque, enabling any-hit shader execution.


## Signature
<pre>
<span class='code_keyword'>static</span> <span class='code_keyword'>const</span> <span class="code_keyword">uint</span> <a href="ray_flag_force_non_opaque-01245679abcdfghjklmno.md" class="code_var">RAY_FLAG_FORCE_NON_OPAQUE</a> = 0x02;
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
