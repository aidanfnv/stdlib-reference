---
layout: stdlib-reference
---

# struct SamplerComparisonState

*Conditionally conforms to:* \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.Sampler\>

## Description

Sampling state for filtered texture fetches that include a comparison operation before filtering.


## Fields

####  <a id="decl-kind"></a>[kind](kind.md) : [DescriptorKind](../descriptorkind-0a/index.md) = [DescriptorKind](../descriptorkind-0a/index.md)\.[Sampler](../descriptorkind-0a/index.md#decl-Sampler)

## Methods

* [init](init.md)

## Conditional Conformances

### Conformance to \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.Sampler\>
`SamplerComparisonState` additionally conforms to `\_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.Sampler\>`.

```{toctree}
:titlesonly:
:hidden:

Handle <../types/samplercomparisonstate-07h/handle-0>
init <../types/samplercomparisonstate-07h/init>
kind <../types/samplercomparisonstate-07h/kind>
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
