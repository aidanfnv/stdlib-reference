---
layout: stdlib-reference
---

# RAY_FLAG_SKIP_CLOSEST_HIT_SHADER

## Description

Skips execution of closest hit shaders, useful for shadow rays.


## Signature
<pre>
<span class='code_keyword'>static</span> <span class='code_keyword'>const</span> <span class="code_keyword">uint</span> <a href="ray_flag_skip_closest_hit_shader-01245679abcefghijkmnoqrstuv.md" class="code_var">RAY_FLAG_SKIP_CLOSEST_HIT_SHADER</a> = 0x08;
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
