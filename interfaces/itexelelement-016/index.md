---
layout: stdlib-reference
---

# interface ITexelElement

## Description

Represent types that can be used as texel element.


## Associated types

#### _Element



Constraints:

  - ITexelElement\.This\.Element : \_\_BuiltinArithmeticType


## Fields

####  <a id="decl-elementCount"></a>[elementCount](elementcount-7.md) : int

## Methods

* [init](init.md)


```{toctree}
:titlesonly:
:hidden:

elementCount <../interfaces/itexelelement-016/elementcount-7>
init <../interfaces/itexelelement-016/init>
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
