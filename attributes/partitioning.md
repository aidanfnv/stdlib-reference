---
layout: stdlib-reference
---

# attribute [partitioning]

## Description

Used on an hull shader entrypoint to specify the patch type used by the hull shader.

## Signature

<pre>
[<a href="partitioning.md">partitioning</a>(<a href="partitioning.md#decl-mode" class="code_param">mode</a>)]
</pre>

## Parameters

####  <a id="decl-mode"></a>mode
The patch type used by the hull shader. Valid values are "tri", "quad" and "isoline".



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
