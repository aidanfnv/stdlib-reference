---
layout: stdlib-reference
---

# HitObject\.TraceRay

## Description

Executes ray traversal (including anyhit and intersection shaders) like TraceRay, but returns the
resulting hit information as a HitObject and does not trigger closesthit or miss shaders.




## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">HitObject</a> <a href="index.md" class="code_type">HitObject</a>.<a href="traceray-05.md">TraceRay</a>&lt;<a href="traceray-05.md#typeparam-payload_t" class="code_type">payload_t</a>&gt;(
    <a href="../raytracingaccelerationstructure-0am/index.md" class="code_type">RaytracingAccelerationStructure</a> <a href="traceray-05.md#decl-AccelerationStructure" class="code_param">AccelerationStructure</a>,
    <span class="code_keyword">uint</span> <a href="traceray-05.md#decl-RayFlags" class="code_param">RayFlags</a>,
    <span class="code_keyword">uint</span> <a href="traceray-05.md#decl-InstanceInclusionMask" class="code_param">InstanceInclusionMask</a>,
    <span class="code_keyword">uint</span> <a href="traceray-05.md#decl-RayContributionToHitGroupIndex" class="code_param">RayContributionToHitGroupIndex</a>,
    <span class="code_keyword">uint</span> <a href="traceray-05.md#decl-MultiplierForGeometryContributionToHitGroupIndex" class="code_param">MultiplierForGeometryContributionToHitGroupIndex</a>,
    <span class="code_keyword">uint</span> <a href="traceray-05.md#decl-MissShaderIndex" class="code_param">MissShaderIndex</a>,
    <a href="../raydesc-03/index.md" class="code_type">RayDesc</a> <a href="traceray-05.md#decl-Ray" class="code_param">Ray</a>,
    <span class="code_keyword">inout</span> <a href="traceray-05.md#typeparam-payload_t" class="code_type">payload_t</a> <a href="traceray-05.md#decl-Payload" class="code_param">Payload</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-payload_t"></a>payload\_t

## Parameters

####  <a id="decl-AccelerationStructure"></a>AccelerationStructure  : [RaytracingAccelerationStructure](../raytracingaccelerationstructure-0am/index.md)
####  <a id="decl-RayFlags"></a>RayFlags  : uint
####  <a id="decl-InstanceInclusionMask"></a>InstanceInclusionMask  : uint
####  <a id="decl-RayContributionToHitGroupIndex"></a>RayContributionToHitGroupIndex  : uint
####  <a id="decl-MultiplierForGeometryContributionToHitGroupIndex"></a>MultiplierForGeometryContributionToHitGroupIndex  : uint
####  <a id="decl-MissShaderIndex"></a>MissShaderIndex  : uint
####  <a id="decl-Ray"></a>Ray  : [RayDesc](../raydesc-03/index.md)
####  <a id="decl-Payload"></a>Payload  : [payload\_t](traceray-05.md#typeparam-payload_t)

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
