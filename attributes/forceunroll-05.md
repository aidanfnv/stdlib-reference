---
layout: stdlib-reference
---

# attribute [ForceUnroll]

## Description

Instructs the Slang compiler to unroll the loop until the specified number of iterations before
emiting targett code.

## Signature

<pre>
[<a href="forceunroll-05.md">ForceUnroll</a>(<a href="forceunroll-05.md#decl-count" class="code_param">count</a> : <span class="code_keyword">int</span>)]
</pre>

## Parameters

####  <a id="decl-count"></a>count  : int = 0
The maximun number of iterations to unroll the loop.



<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
