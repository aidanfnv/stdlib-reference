---
layout: stdlib-reference
---

# HitObject\.Invoke

## Description

Invokes closesthit or miss shading for the specified hit object. In case of a NOP HitObject, no
shader is invoked.




## Signature 

<pre>
<span class='code_keyword'>static</span> <span class="code_keyword">void</span> <a href="index.md" class="code_type">HitObject</a>.<a href="invoke-0.md">Invoke</a>&lt;<a href="invoke-0.md#typeparam-payload_t" class="code_type">payload_t</a>&gt;(
    <a href="../raytracingaccelerationstructure-0am/index.md" class="code_type">RaytracingAccelerationStructure</a> <a href="invoke-0.md#decl-AccelerationStructure" class="code_param">AccelerationStructure</a>,
    <a href="index.md" class="code_type">HitObject</a> <a href="invoke-0.md#decl-HitOrMiss" class="code_param">HitOrMiss</a>,
    <span class="code_keyword">inout</span> <a href="invoke-0.md#typeparam-payload_t" class="code_type">payload_t</a> <a href="invoke-0.md#decl-Payload" class="code_param">Payload</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-payload_t"></a>payload\_t

## Parameters

####  <a id="decl-AccelerationStructure"></a>AccelerationStructure  : [RaytracingAccelerationStructure](../raytracingaccelerationstructure-0am/index.md)
####  <a id="decl-HitOrMiss"></a>HitOrMiss  : [HitObject](index.md)
####  <a id="decl-Payload"></a>Payload  : [payload\_t](invoke-0.md#typeparam-payload_t)

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
