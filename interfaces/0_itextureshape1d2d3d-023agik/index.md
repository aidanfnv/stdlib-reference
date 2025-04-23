---
layout: stdlib-reference
---

# interface \_\_ITextureShape1D2D3D

*Inherits from:* [\_\_ITextureShape](../0_itextureshape-023a/index.md)

> #### Internal Feature
> The feature described in this page is marked as an internal implementation detail, and is not intended for use by end-users.
> Users are advised to avoid using this declaration directly, as it may be removed or changed in future releases.

## Description

Represent a 1D, 2D or 3D texture shape that can be used as the <span class='code'>Shape</span> parameter of the <span class='code'><a href="../../types/0texture-01/index.md" class="code_type">_Texture</a></span> type.

Implemented by <span class='code'><a href="../../types/0_shape1d-028/index.md" class="code_type">__Shape1D</a></span>, <span class='code'><a href="../../types/0_shape2d-028/index.md" class="code_type">__Shape2D</a></span> and <span class='code'><a href="../../types/0_shape3d-028/index.md" class="code_type">__Shape3D</a></span>.


## See also

<span class='code'><a href="../../types/0texture-01/index.md" class="code_type">_Texture</a></span>.


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
