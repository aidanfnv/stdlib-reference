---
layout: stdlib-reference
---

# IArithmetic\.mod

## Description

Computes the remainder of division of one value of the conforming type by another.



## Signature 

<pre>
<a href="index.md" class="code_type">IArithmetic</a>.<span class="code_keyword">This</span> <a href="index.md" class="code_type">IArithmetic</a>.<a href="mod.md">mod</a>(<a href="index.md" class="code_type">IArithmetic</a>.<span class="code_keyword">This</span> <a href="mod.md#decl-other" class="code_param">other</a>);

</pre>

## Parameters

####  <a id="decl-other"></a>other  : [IArithmetic](index.md)\.This
The divisor used to divide <span class='code'>this</span>.


## Return value
The remainder of <span class='code'>this</span> divided by <span class='code'><a href="mod.md#decl-other" class="code_param">other</a></span>.



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
