---
layout: stdlib-reference
---

# struct SAMPLER\_FEEDBACK\_MIP\_REGION\_USED

*Conforms to:* \_\_BuiltinSamplerFeedbackType, [ITexelElement](../../interfaces/itexelelement-016/index.md)

## Description



## Fields

####  <a id="decl-elementCount"></a>[elementCount](elementcount-7.md) : int = 1

## Methods

* [init](init.md)


```{toctree}
:titlesonly:
:hidden:

Element <../types/sampler_feedback_mip_region_used-012345689abcdefhijlmnopqstuv/element-0>
elementCount <../types/sampler_feedback_mip_region_used-012345689abcdefhijlmnopqstuv/elementcount-7>
init <../types/sampler_feedback_mip_region_used-012345689abcdefhijlmnopqstuv/init>
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
