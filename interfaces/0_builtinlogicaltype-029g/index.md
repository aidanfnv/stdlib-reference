---
layout: stdlib-reference
---

# interface \_\_BuiltinLogicalType

*Inherits from:* \_\_BuiltinType, [ILogical](../ilogical-01/index.md)

## Description

A type that can be used for logical/bitwise operations. For defining generic functions that work with builtin scalar logical types only.
Builtin types implementing this interface: <span class='code'><span class="code_keyword">bool</span></span>, <span class='code'>int8_t</span>, <span class='code'>uint8_t</span>, <span class='code'>int16_t</span>, <span class='code'>uint16_t</span>, <span class='code'><span class="code_keyword">int</span></span>, <span class='code'><span class="code_keyword">uint</span></span>, <span class='code'>int64_t</span>, <span class='code'>uint64_t</span>.



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
