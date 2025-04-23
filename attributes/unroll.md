---
layout: stdlib-reference
---

# attribute [unroll]

## Description

A hint to the downstream compiler to unroll the loop until the specified number of iterations reached.
This attribute does not affect Slang compiler's behavior.
To unroll a loop in the Slang compiler before emitting target code, use the <span class='code'>[<a href="forceunroll-05.md">ForceUnroll</a>]</span> attribute.


## Signature

<pre>
[<a href="unroll.md">unroll</a>(<a href="unroll.md#decl-count" class="code_param">count</a> : <span class="code_keyword">int</span>)]
</pre>

## Parameters

####  <a id="decl-count"></a>count  : int = 0


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
