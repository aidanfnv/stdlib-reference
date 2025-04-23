---
layout: stdlib-reference
---

# attribute [DerivativeGroupLinear]

## Description

Mark a compute shader entry point to allow it to use implicit derivatives.

## Signature

<pre>
[<a href="derivativegrouplinear-0af.md">DerivativeGroupLinear</a>]
</pre>

## Remarks

This attributes causes Slang to emit <span class='code'>DerivativeGroupLinearNV</span> execution mode when producing SPIR-V. The attribute has no
effect on other targets.



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
