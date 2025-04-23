---
layout: stdlib-reference
---

# typealias TextureFootprint2D

## Description



## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="texturefootprint2d-07h.md" class="code_type">TextureFootprint2D</a> = <a href="texturefootprint-07/index.md" class="code_type">TextureFootprint</a>&lt;2&gt;;
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
