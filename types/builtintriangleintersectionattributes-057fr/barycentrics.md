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
      const href = link.getAttribute('href');
      if (href && href.includes('.md')) {
        // This regex will handle .md links with or without fragment identifiers or query parameters
        link.href = link.href.replace(/(.+)\.md(#[^?]*)?(\?.*)?$/, '$1.html$2$3');
      }
    });
  });
}
</script>
