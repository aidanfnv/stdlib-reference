---
layout: stdlib-reference
---

# RayDesc.TMin

## Description

Minimum distance along the ray to consider intersections.


## Signature
<pre>
<span class="code_keyword">float</span> <a href="index.md" class="code_type">RayDesc</a>.<a href="tmin-01.md" class="code_var">TMin</a>;
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
