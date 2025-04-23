---
layout: stdlib-reference
---

# attribute [PreferCheckpoint]

## Description

Mark a differentiable function to prefer checkpointing over recomputation when a value computed in the primal pass is needed
during backward derivative propagation.


## Signature

<pre>
[<a href="prefercheckpoint-06.md">PreferCheckpoint</a>]
</pre>


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
