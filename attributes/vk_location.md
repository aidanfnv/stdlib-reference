---
layout: stdlib-reference
---

# attribute [vk::location]

## Description

Declare the Vulkan location of a global variable.


## Signature

<pre>
[vk::<a href="vk_location.md#decl-location" class="code_param">location</a>(<a href="vk_location.md#decl-location" class="code_param">location</a> : <span class="code_keyword">int</span>)]
</pre>

## Parameters

####  <a id="decl-location"></a>location  : int


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
