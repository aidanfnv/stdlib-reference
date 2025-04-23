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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
