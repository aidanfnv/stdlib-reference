---
layout: stdlib-reference
---

# ILogical\.not

## Description

Performs a logical NOT operation on this value, returning the logical negation.




## Signature 

<pre>
<a href="index.md" class="code_type">ILogical</a>.<span class="code_keyword">This</span> <a href="index.md" class="code_type">ILogical</a>.<a href="not.md">not</a>();

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
