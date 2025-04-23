---
layout: stdlib-reference
---

# attribute [call]

## Description

A hint to the downstream compiler to translate the <span class='code'>switch</span> statement into subroutine calls.
This attribute has no effect on targets other than HLSL.


## Signature

<pre>
[<a href="call.md">call</a>]
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
