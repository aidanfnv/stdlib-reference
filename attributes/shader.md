---
layout: stdlib-reference
---

# attribute [shader]

## Description

Marks a function as a shader entry point.

## Signature

<pre>
[<a href="shader.md">shader</a>(<a href="shader.md#decl-stage" class="code_param">stage</a>)]
</pre>

## Parameters

####  <a id="decl-stage"></a>stage
The stage of the shader. Must be one of "vertex", "fragment", "compute", "geometry", "hull", "domain", "raygeneration",



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
