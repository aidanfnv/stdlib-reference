---
layout: stdlib-reference
---

# ILogical\.shl

## Description

Shifts the bits of this value to the left by the specified number of positions.




## Signature 

<pre>
<a href="index.md" class="code_type">ILogical</a>.<span class="code_keyword">This</span> <a href="index.md" class="code_type">ILogical</a>.<a href="shl.md">shl</a>(<span class="code_keyword">int</span> <a href="shl.md#decl-value" class="code_param">value</a>);

</pre>

## Parameters

####  <a id="decl-value"></a>value  : int


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
