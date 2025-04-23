---
layout: stdlib-reference
---

# struct \_\_Shape2D

*Conforms to:* [\_\_ITextureShape1D2D3D](../../interfaces/0_itextureshape1d2d3d-023agik/index.md)

## Description

When used as the <span class='code'>Shape</span> parameter of the <span class='code'><a href="../0texture-01/index.md" class="code_type">_Texture</a></span> type, specifies a 2D texture.


## Fields

####  <a id="decl-dimensions"></a>[dimensions](dimensions.md) : int = 2
####  <a id="decl-flavor"></a>[flavor](flavor.md) : int = 2
####  <a id="decl-planeDimensions"></a>[planeDimensions](planedimensions-5.md) : int = 2


```{toctree}
:titlesonly:
:hidden:

dimensions <../types/0_shape2d-028/dimensions>
flavor <../types/0_shape2d-028/flavor>
planeDimensions <../types/0_shape2d-028/planedimensions-5>
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
