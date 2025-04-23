---
layout: stdlib-reference
---

# RayDesc.Origin

## Description

Starting point of the ray in world space.


## Signature
<pre>
<a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="index.md" class="code_type">RayDesc</a>.<a href="origin-0.md" class="code_var">Origin</a>;
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
