---
layout: stdlib-reference
---

# attribute [vk::spirv\_instruction]

> #### Deprecated Feature
> The feature described in this page is marked as deprecated, and may be removed in a future release.
> Users are advised to avoid using this feature, and to migrate to a newer alternative.

## Description

Use <span class='code'>spirv_asm</span> instead for inline SPIR-V assembly.


## Signature

<pre>
[vk::spirv_instruction(<a href="vk_spirv_instruction.md#decl-op" class="code_param">op</a> : <span class="code_keyword">int</span>, <a href="vk_spirv_instruction.md#decl-set" class="code_keyword">set</a> : <a href="../types/string-0/index.md" class="code_type">String</a>)]
</pre>

## Parameters

####  <a id="decl-op"></a>op  : int
####  <a id="decl-set"></a>set  : [String](../types/string-0/index.md) = ""


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
