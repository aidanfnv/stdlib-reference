---
layout: stdlib-reference
---

# extension T : ITexelElement

*Conforms to:* [ITexelElement](../../interfaces/itexelelement-016/index.md)

*Conditionally conforms to:* [ITexelElement](../../interfaces/itexelelement-016/index.md)

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../../interfaces/0_builtinarithmetictype-029j/index.md)

## Fields

####  <a id="decl-elementCount"></a>[elementCount](elementcount-7.md) : int = 1

## Methods

* [init](init.md)

## Conditional Conformances

### Conformance to ITexelElement
`<T>` additionally conforms to `ITexelElement`.

```{toctree}
:titlesonly:
:hidden:

Element <../types/t-0/element-0>
elementCount <../types/t-0/elementcount-7>
init <../types/t-0/init>
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
