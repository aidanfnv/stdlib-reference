---
layout: stdlib-reference
---

# struct SamplerState

*Conditionally conforms to:* \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.Sampler\>

## Description

Sampling state for filtered texture fetches.


## Fields

####  <a id="decl-kind"></a>[kind](kind.md) : [DescriptorKind](../descriptorkind-0a/index.md) = [DescriptorKind](../descriptorkind-0a/index.md)\.[Sampler](../descriptorkind-0a/index.md#decl-Sampler)

## Methods

* [init](init.md)

## Conditional Conformances

### Conformance to \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.Sampler\>
`SamplerState` additionally conforms to `\_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.Sampler\>`.

```{toctree}
:titlesonly:
:hidden:

Handle <../types/samplerstate-07/handle-0>
init <../types/samplerstate-07/init>
kind <../types/samplerstate-07/kind>
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
