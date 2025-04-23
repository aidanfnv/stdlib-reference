---
layout: stdlib-reference
---

# IArithmetic\.neg

## Description

Negates a value of the conforming type.



## Signature 

<pre>
<a href="index.md" class="code_type">IArithmetic</a>.<span class="code_keyword">This</span> <a href="index.md" class="code_type">IArithmetic</a>.<a href="neg.md">neg</a>();

</pre>

## Return value
The negation of <span class='code'>this</span>.



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
