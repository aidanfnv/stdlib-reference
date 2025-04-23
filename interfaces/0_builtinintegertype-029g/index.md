---
layout: stdlib-reference
---

# interface \_\_BuiltinIntegerType

*Inherits from:* [\_\_BuiltinArithmeticType](../0_builtinarithmetictype-029j/index.md), [IInteger](../iinteger-01/index.md)

## Description

Represents builtin types that can represent integers.



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
