---
layout: stdlib-reference
---

# HIT_KIND_TRIANGLE_BACK_FACE

## Description

Predefined hit kind value for back-facing triangle intersections.


## Signature
<pre>
<span class='code_keyword'>static</span> <span class='code_keyword'>const</span> <span class="code_keyword">uint</span> <a href="hit_kind_triangle_back_face-01245679abcdefgijklnopq.md" class="code_var">HIT_KIND_TRIANGLE_BACK_FACE</a> = 255;
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
