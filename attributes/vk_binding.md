---
layout: stdlib-reference
---

# attribute [vk::binding]

## Description

Declare the Vulkan binding location of a global shader variable.

## Signature

<pre>
[vk::<a href="vk_binding.md#decl-binding" class="code_param">binding</a>(<a href="vk_binding.md#decl-binding" class="code_param">binding</a> : <span class="code_keyword">int</span>, <a href="vk_binding.md#decl-set" class="code_keyword">set</a> : <span class="code_keyword">int</span>)]
</pre>

## Parameters

####  <a id="decl-binding"></a>binding  : int
The binding location.

####  <a id="decl-set"></a>set  : int = 0
The descriptor set index of the binding.



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
