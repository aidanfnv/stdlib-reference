---
layout: stdlib-reference
---

# interface IRangedValue

## Description

Represents types that has a defined range of values.
Implemented by all builtin integer and floating point types.


## Fields

####  <a id="decl-maxValue"></a>[maxValue](maxvalue-3.md) : [IRangedValue](index.md)\.This
The maximum value that an instance of the type can hold.
This is a constant value specific to the type.

####  <a id="decl-minValue"></a>[minValue](minvalue-3.md) : [IRangedValue](index.md)\.This
The minimum value that an instance of the type can hold.
This is a constant value specific to the type.



```{toctree}
:titlesonly:
:hidden:

maxValue <../interfaces/irangedvalue-017/maxvalue-3>
minValue <../interfaces/irangedvalue-017/minvalue-3>
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
