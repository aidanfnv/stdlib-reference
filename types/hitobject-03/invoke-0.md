---
layout: stdlib-reference
---

# HitObject\.Invoke

## Description

Invokes closesthit or miss shading for the specified hit object. In case of a NOP HitObject, no
shader is invoked.




## Signature 

<pre>
<span class='code_keyword'>static</span> <span class="code_keyword">void</span> <a href="../types/hitobject-03/index" class="code_type">HitObject</a>.<a href="invoke-0">Invoke</a>&lt;<a href="invoke-0#typeparam-payload_t" class="code_type">payload_t</a>&gt;(
    <a href="../types/raytracingaccelerationstructure-0am/index" class="code_type">RaytracingAccelerationStructure</a> <a href="invoke-0#decl-AccelerationStructure" class="code_param">AccelerationStructure</a>,
    <a href="../types/hitobject-03/index" class="code_type">HitObject</a> <a href="invoke-0#decl-HitOrMiss" class="code_param">HitOrMiss</a>,
    <span class="code_keyword">inout</span> <a href="invoke-0#typeparam-payload_t" class="code_type">payload_t</a> <a href="invoke-0#decl-Payload" class="code_param">Payload</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-payload_t"></a>payload\_t

## Parameters

####  <a id="decl-AccelerationStructure"></a>AccelerationStructure  : [RaytracingAccelerationStructure](../types/raytracingaccelerationstructure-0am/index)
####  <a id="decl-HitOrMiss"></a>HitOrMiss  : [HitObject](../types/hitobject-03/index)
####  <a id="decl-Payload"></a>Payload  : [payload\_t](invoke-0#typeparam-payload_t)

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


