---
layout: stdlib-reference
---

# HitObject\.GetAttributes

## Description

Returns the attributes of a hit. Valid if the hit object represents a hit or a miss.




## Signature 

<pre>
<a href="getattributes-03.md#typeparam-attr_t" class="code_type">attr_t</a> <a href="index.md" class="code_type">HitObject</a>.<a href="getattributes-03.md">GetAttributes</a>&lt;<a href="getattributes-03.md#typeparam-attr_t" class="code_type">attr_t</a>&gt;();

</pre>

## Generic Parameters

####  <a id="typeparam-attr_t"></a>attr\_t

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
