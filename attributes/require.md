---
layout: stdlib-reference
---

# attribute [require]

## Description

Mark declaration to require a specific target capability.

## Signature

<pre>
[<a href="require.md">require</a>(<a href="require.md#decl-capability" class="code_param">capability</a>)]
</pre>

## Parameters

####  <a id="decl-capability"></a>capability
The required capability.



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
