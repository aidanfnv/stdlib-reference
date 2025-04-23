---
layout: stdlib-reference
---

# IFloat\.toFloat

## Description

Converts a value of the conforming type into a <span class='code'><span class="code_keyword">float</span></span>.




## Signature 

<pre>
<span class="code_keyword">float</span> <a href="index.md" class="code_type">IFloat</a>.<a href="tofloat-2.md">toFloat</a>();

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
