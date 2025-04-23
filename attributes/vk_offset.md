---
layout: stdlib-reference
---

# attribute [vk::offset]

## Description

Declare offset for a struct field. Applies to all kinds of structs when targeting Vulkan.
Applies only to structs that are directly used as interface blocks (such as push constants and uniforms)
when targeting GLSL, as GLSL does not support the <span class='code'>offset</span> qualifier on regular structs.
This attribute has no effect on other targets.


## Signature

<pre>
[vk::offset(<a href="vk_offset.md#decl-index" class="code_param">index</a> : <span class="code_keyword">int</span>)]
</pre>

## Parameters

####  <a id="decl-index"></a>index  : int


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
