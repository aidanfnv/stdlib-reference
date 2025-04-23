---
layout: stdlib-reference
---

# attribute [UnscopedEnum]

## Description

Marks a enum type as an unscoped enum. The enum cases of an unscoped enum are not scoped within the enum type, and can be
referenced directly without the enum type name.


## Signature

<pre>
[<a href="unscopedenum-08.md">UnscopedEnum</a>]
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
