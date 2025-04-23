---
layout: stdlib-reference
---

# attribute [outputtopology]

## Description

Used on an hull shader entrypoint to declare the output primitive type of the tessellator.

## Signature

<pre>
[<a href="outputtopology.md">outputtopology</a>(<a href="outputtopology.md#decl-topology" class="code_param">topology</a>)]
</pre>

## Parameters

####  <a id="decl-topology"></a>topology
The output primitive type, must be one of "point", "line", "triangle_cw", and "triangle_ccw".



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
