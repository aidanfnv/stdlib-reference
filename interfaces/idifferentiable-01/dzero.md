---
layout: stdlib-reference
---

# IDifferentiable\.dzero

## Description

Returns a zero-initialized value of the differential type.




## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">IDifferentiable</a>.<span class="code_keyword">This</span>.Differential <a href="index.md" class="code_type">IDifferentiable</a>.<a href="dzero.md">dzero</a>();

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
