---
layout: stdlib-reference
---

# attribute [MaximallyReconverges]

## Description

Emits <span class='code'>MaximallyReconvergesKHR</span> execution mode when producing SPIR-V.
This attribute has no effect on other targets.


## Signature

<pre>
[<a href="maximallyreconverges-09.md">MaximallyReconverges</a>]
</pre>


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
