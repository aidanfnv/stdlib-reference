---
layout: stdlib-reference
---

# struct \_\_Shape1D

*Conforms to:* [\_\_ITextureShape1D2D3D](../../interfaces/0_itextureshape1d2d3d-023agik/index.md)

## Description

When used as the <span class='code'>Shape</span> parameter of the <span class='code'><a href="../0texture-01/index.md" class="code_type">_Texture</a></span> type, specifies a 1D texture.


## Fields

####  <a id="decl-dimensions"></a>[dimensions](dimensions.md) : int = 1
####  <a id="decl-flavor"></a>[flavor](flavor.md) : int = 1
####  <a id="decl-planeDimensions"></a>[planeDimensions](planedimensions-5.md) : int = 1


```{toctree}
:titlesonly:
:hidden:

dimensions <../types/0_shape1d-028/dimensions>
flavor <../types/0_shape1d-028/flavor>
planeDimensions <../types/0_shape1d-028/planedimensions-5>
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
