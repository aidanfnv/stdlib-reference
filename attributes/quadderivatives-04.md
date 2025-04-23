---
layout: stdlib-reference
---

# attribute [QuadDerivatives]

## Description

Emits <span class='code'>QuadDerivativesKHR</span> execution mode when producing SPIR-V.
This attribute has no effect on other targets.


## Signature

<pre>
[<a href="quadderivatives-04.md">QuadDerivatives</a>]
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
