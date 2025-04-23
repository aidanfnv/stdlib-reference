---
layout: stdlib-reference
---

# attribute [WaveSize]

## Description

Indicate a compute shader entry point is only compatible with the specified wave size.

## Signature

<pre>
[<a href="wavesize-04.md">WaveSize</a>(<a href="wavesize-04.md#decl-numLanes" class="code_param">numLanes</a> : <span class="code_keyword">int</span>)]
</pre>

## Parameters

####  <a id="decl-numLanes"></a>numLanes  : int
The wave size this shader entrypoint is compatible with. Must be one of 4, 8, 16, 32, 64, 128.



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
