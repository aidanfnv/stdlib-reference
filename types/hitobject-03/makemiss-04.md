---
layout: stdlib-reference
---

# HitObject\.MakeMiss

## Description

Creates a HitObject representing a miss based on values explicitly passed as arguments, without
tracing a ray. The provided shader table index must reference a valid miss record in the shader
table.




## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">HitObject</a> <a href="index.md" class="code_type">HitObject</a>.<a href="makemiss-04.md">MakeMiss</a>(
    <span class="code_keyword">uint</span> <a href="makemiss-04.md#decl-MissShaderIndex" class="code_param">MissShaderIndex</a>,
    <a href="../raydesc-03/index.md" class="code_type">RayDesc</a> <a href="makemiss-04.md#decl-Ray" class="code_param">Ray</a>);

</pre>

## Parameters

####  <a id="decl-MissShaderIndex"></a>MissShaderIndex  : uint
####  <a id="decl-Ray"></a>Ray  : [RayDesc](../raydesc-03/index.md)

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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
