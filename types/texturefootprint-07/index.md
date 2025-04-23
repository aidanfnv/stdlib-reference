---
layout: stdlib-reference
---

# struct TextureFootprint\<ND:int\>

*Conforms to:* \_\_TextureFootprintData\<[ND](index.md#decl-ND)\>

## Description



## Generic Parameters

####  <a id="decl-ND"></a>ND  : int

## Fields

####  <a id="decl-_isSingleLevel"></a>[\_isSingleLevel](0issinglelevel-039.md) : bool

## Properties

####  <a id="decl-isSingleLevel"></a>[isSingleLevel](issinglelevel-28.md)

## Methods

* init


```{toctree}
:titlesonly:
:hidden:

_isSingleLevel <../types/texturefootprint-07/0issinglelevel-039>
isSingleLevel <../types/texturefootprint-07/issinglelevel-28>
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
