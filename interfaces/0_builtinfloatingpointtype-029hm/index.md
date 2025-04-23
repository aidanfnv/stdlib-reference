---
layout: stdlib-reference
---

# interface \_\_BuiltinFloatingPointType

*Inherits from:* \_\_BuiltinRealType, [IFloat](../ifloat-01/index.md)

## Description

Represents builtin floating point scalar types.
To define generic functions that work with both scalar and vector types, use <span class='code'><a href="../ifloat-01/index.md" class="code_type">IFloat</a></span> instead.

Implemented by <span class='code'><span class="code_keyword">float</span></span>, <span class='code'><span class="code_keyword">half</span></span> and <span class='code'><span class="code_keyword">double</span></span> types.


## Methods

* [getPi](getpi-3.md)


```{toctree}
:titlesonly:
:hidden:

getPi <../interfaces/0_builtinfloatingpointtype-029hm/getpi-3>
```

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
