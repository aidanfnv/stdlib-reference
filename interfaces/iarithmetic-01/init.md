---
layout: stdlib-reference
---

# IArithmetic\.init

## Description

Initialize from the same type.




## Signature 

<pre>
<a href="index.md" class="code_type">IArithmetic</a>.<a href="init.md">init</a>(<span class="code_keyword">int</span> <a href="init.md#decl-val" class="code_param">val</a>);

<a href="index.md" class="code_type">IArithmetic</a>.<a href="init.md">init</a>(<a href="index.md" class="code_type">IArithmetic</a>.<span class="code_keyword">This</span> <a href="init.md#decl-value" class="code_param">value</a>);

</pre>

## Parameters

####  <a id="decl-val"></a>val  : int
####  <a id="decl-value"></a>value  : [IArithmetic](index.md)\.This


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
