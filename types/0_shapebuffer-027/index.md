---
layout: stdlib-reference
---

# struct \_\_ShapeBuffer

*Conforms to:* [\_\_ITextureShape](../../interfaces/0_itextureshape-023a/index.md)

## Description

When used as the <span class='code'>Shape</span> parameter of the <span class='code'><a href="../0texture-01/index.md" class="code_type">_Texture</a></span> type, specifies a buffer texture.


## Fields

####  <a id="decl-dimensions"></a>[dimensions](dimensions.md) : int = 1
####  <a id="decl-flavor"></a>[flavor](flavor.md) : int = 5
####  <a id="decl-planeDimensions"></a>[planeDimensions](planedimensions-5.md) : int = 1


```{toctree}
:titlesonly:
:hidden:

dimensions <../types/0_shapebuffer-027/dimensions>
flavor <../types/0_shapebuffer-027/flavor>
planeDimensions <../types/0_shapebuffer-027/planedimensions-5>
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
