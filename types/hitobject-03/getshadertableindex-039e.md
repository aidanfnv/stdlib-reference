---
layout: stdlib-reference
---

# HitObject\.GetShaderTableIndex

## Description

Queries shader table index from HitObject. Valid if the hit object represents a hit or a miss.




## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/index" class="code_type">HitObject</a>.<a href="/stdlib-reference/types/hitobject-03/getshadertableindex-039e">GetShaderTableIndex</a>();

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


