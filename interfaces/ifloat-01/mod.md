---
layout: stdlib-reference
---

# IFloat\.mod

## Description

Computes the arithmetic remainder from values of the conforming type.




## Signature 

<pre>
<a href="index.md" class="code_type">IFloat</a>.<span class="code_keyword">This</span> <a href="index.md" class="code_type">IFloat</a>.<a href="mod.md">mod</a>(<a href="index.md" class="code_type">IFloat</a>.<span class="code_keyword">This</span> <a href="mod.md#decl-other" class="code_param">other</a>);

</pre>

## Parameters

####  <a id="decl-other"></a>other  : [IFloat](index.md)\.This


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
