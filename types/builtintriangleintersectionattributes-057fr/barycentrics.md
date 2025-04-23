---
layout: stdlib-reference
---

# BuiltInTriangleIntersectionAttributes.barycentrics

## Description

Barycentric coordinates of the intersection point on the triangle.


## Signature
<pre>
<a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="index.md" class="code_type">BuiltInTriangleIntersectionAttributes</a>.<a href="barycentrics.md" class="code_var">barycentrics</a>;
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
