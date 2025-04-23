---
layout: stdlib-reference
---

# attribute [DerivativeGroupQuad]

## Description

Mark a compute shader entry point to allow it to use implicit derivatives.

## Signature

<pre>
[<a href="derivativegroupquad-0af.md">DerivativeGroupQuad</a>]
</pre>

## Remarks

This attributes causes Slang to emit <span class='code'>DerivativeGroupQuadsNV</span> execution mode when producing SPIR-V. The attribute has no
effect on other targets.



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
