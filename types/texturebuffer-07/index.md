---
layout: stdlib-reference
---

# struct TextureBuffer\<T\>

*Conditionally conforms to:* \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>

## Description



## Generic Parameters

####  <a id="typeparam-T"></a>T

## Fields

####  <a id="decl-kind"></a>[kind](kind.md) : [DescriptorKind](../descriptorkind-0a/index.md) = [DescriptorKind](../descriptorkind-0a/index.md)\.[Buffer](../descriptorkind-0a/index.md#decl-Buffer)

## Methods

* [init](init.md)

## Conditional Conformances

### Conformance to \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>
`TextureBuffer<T>` additionally conforms to `\_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>`.

```{toctree}
:titlesonly:
:hidden:

Handle <../types/texturebuffer-07/handle-0>
init <../types/texturebuffer-07/init>
kind <../types/texturebuffer-07/kind>
```

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
