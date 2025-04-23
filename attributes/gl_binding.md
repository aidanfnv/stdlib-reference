---
layout: stdlib-reference
---

# attribute [gl\_binding]

## Description

Declare the Vulkan binding location of a global shader variable.

## Signature

<pre>
[<a href="gl_binding.md">gl_binding</a>(<a href="gl_binding.md#decl-binding" class="code_param">binding</a> : <span class="code_keyword">int</span>, <a href="gl_binding.md#decl-set" class="code_keyword">set</a> : <span class="code_keyword">int</span>)]
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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
