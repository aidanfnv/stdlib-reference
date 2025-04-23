---
layout: stdlib-reference
---

# HitObject\.MakeNop

## Description

Creates a HitObject representing 429496726642949671684294967196NOP429496726642949671684294967197 (no operation) which is neither a hit nor a miss. Invoking a
NOP hit object using HitObject::Invoke has no effect. Reordering by hit objects using
ReorderThread will group NOP hit objects together. This can be useful in some reordering
scenarios where future control flow for some threads is known to process neither a hit nor a
miss.




## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">HitObject</a> <a href="index.md" class="code_type">HitObject</a>.<a href="makenop-04.md">MakeNop</a>();

</pre>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `raygen`, `closesthit`, `miss`.

Requires capability: `hlsl_nvapi`.
#### glsl
Available in stages: `raygen`, `closesthit`, `miss`.

#### spirv
Available in stages: `raygen`, `closesthit`, `miss`.

Requires capabilities: `spvRayTracingKHR`, `spvShaderInvocationReorderNV`.



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
