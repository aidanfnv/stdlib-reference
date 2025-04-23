---
layout: stdlib-reference
---

# attribute [vk::constant\_id]

## Description

Mark a global variable as a Vulkan specialization constant.

## Signature

<pre>
[vk::constant_id(<a href="vk_constant_id.md#decl-location" class="code_param">location</a> : <span class="code_keyword">int</span>)]
</pre>

## Parameters

####  <a id="decl-location"></a>location  : int
The index of the specialization constant.



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
