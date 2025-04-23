---
layout: stdlib-reference
---

# attribute [vk::image\_format]

## Description

Specify the storage format of a read-write texture. Can only be used on a texture typed struct field or global parameter.
This is an alias of the <span class='code'>[<a href="vk_image_format.md#decl-format" class="code_param">format</a>]</span> attribute.

## Signature

<pre>
[vk::image_format(<a href="vk_image_format.md#decl-format" class="code_param">format</a> : <a href="../types/string-0/index.md" class="code_type">String</a>)]
</pre>

## Parameters

####  <a id="decl-format"></a>format  : [String](../types/string-0/index.md)
The storage format of the texture.


## See also

Please refer to <span class='code'><a href="../types/0texture-01/index.md" class="code_type">_Texture</a></span> for a complete list of allowed format strings.



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
