---
layout: stdlib-reference
---

# struct \_\_ShapeCube

*Conforms to:* [\_\_ITextureShape](../../interfaces/0_itextureshape-023a/index.md)

## Description

When used as the <span class='code'>Shape</span> parameter of the <span class='code'><a href="../0texture-01/index.md" class="code_type">_Texture</a></span> type, specifies a Cube texture.


## Fields

####  <a id="decl-dimensions"></a>[dimensions](dimensions.md) : int = 3
####  <a id="decl-flavor"></a>[flavor](flavor.md) : int = 4
####  <a id="decl-planeDimensions"></a>[planeDimensions](planedimensions-5.md) : int = 2


```{toctree}
:titlesonly:
:hidden:

dimensions <../types/0_shapecube-027/dimensions>
flavor <../types/0_shapecube-027/flavor>
planeDimensions <../types/0_shapecube-027/planedimensions-5>
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
