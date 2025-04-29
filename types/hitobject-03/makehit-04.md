---
layout: stdlib-reference
---

# HitObject\.MakeHit

## Description

Creates a HitObject representing a hit based on values explicitly passed as arguments, without
tracing a ray. The primitive specified by AccelerationStructure, InstanceIndex, GeometryIndex,
and PrimitiveIndex must exist. The shader table index is computed using the formula used with
TraceRay. The computed index must reference a valid hit group record in the shader table. The
Attributes parameter must either be an attribute struct, such as
BuiltInTriangleIntersectionAttributes, or another HitObject to copy the attributes from.




## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="../types/hitobject-03/index" class="code_type">HitObject</a> <a href="../types/hitobject-03/index" class="code_type">HitObject</a>.<a href="makehit-04">MakeHit</a>&lt;<a href="makehit-04#typeparam-attr_t" class="code_type">attr_t</a>&gt;(
    <a href="../types/raytracingaccelerationstructure-0am/index" class="code_type">RaytracingAccelerationStructure</a> <a href="makehit-04#decl-AccelerationStructure" class="code_param">AccelerationStructure</a>,
    <span class="code_keyword">uint</span> <a href="makehit-04#decl-InstanceIndex" class="code_param">InstanceIndex</a>,
    <span class="code_keyword">uint</span> <a href="makehit-04#decl-GeometryIndex" class="code_param">GeometryIndex</a>,
    <span class="code_keyword">uint</span> <a href="makehit-04#decl-PrimitiveIndex" class="code_param">PrimitiveIndex</a>,
    <span class="code_keyword">uint</span> <a href="makehit-04#decl-HitKind" class="code_param">HitKind</a>,
    <span class="code_keyword">uint</span> <a href="makehit-04#decl-RayContributionToHitGroupIndex" class="code_param">RayContributionToHitGroupIndex</a>,
    <span class="code_keyword">uint</span> <a href="makehit-04#decl-MultiplierForGeometryContributionToHitGroupIndex" class="code_param">MultiplierForGeometryContributionToHitGroupIndex</a>,
    <a href="../types/raydesc-03/index" class="code_type">RayDesc</a> <a href="makehit-04#decl-Ray" class="code_param">Ray</a>,
    <a href="makehit-04#typeparam-attr_t" class="code_type">attr_t</a> <a href="makehit-04#decl-attributes" class="code_param">attributes</a>);

<span class='code_keyword'>static</span> <a href="../types/hitobject-03/index" class="code_type">HitObject</a> <a href="../types/hitobject-03/index" class="code_type">HitObject</a>.<a href="makehit-04">MakeHit</a>&lt;<a href="makehit-04#typeparam-attr_t" class="code_type">attr_t</a>&gt;(
    <span class="code_keyword">uint</span> <a href="makehit-04#decl-HitGroupRecordIndex" class="code_param">HitGroupRecordIndex</a>,
    <a href="../types/raytracingaccelerationstructure-0am/index" class="code_type">RaytracingAccelerationStructure</a> <a href="makehit-04#decl-AccelerationStructure" class="code_param">AccelerationStructure</a>,
    <span class="code_keyword">uint</span> <a href="makehit-04#decl-InstanceIndex" class="code_param">InstanceIndex</a>,
    <span class="code_keyword">uint</span> <a href="makehit-04#decl-GeometryIndex" class="code_param">GeometryIndex</a>,
    <span class="code_keyword">uint</span> <a href="makehit-04#decl-PrimitiveIndex" class="code_param">PrimitiveIndex</a>,
    <span class="code_keyword">uint</span> <a href="makehit-04#decl-HitKind" class="code_param">HitKind</a>,
    <a href="../types/raydesc-03/index" class="code_type">RayDesc</a> <a href="makehit-04#decl-Ray" class="code_param">Ray</a>,
    <a href="makehit-04#typeparam-attr_t" class="code_type">attr_t</a> <a href="makehit-04#decl-attributes" class="code_param">attributes</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-attr_t"></a>attr\_t

## Parameters

####  <a id="decl-AccelerationStructure"></a>AccelerationStructure  : [RaytracingAccelerationStructure](../types/raytracingaccelerationstructure-0am/index)
####  <a id="decl-InstanceIndex"></a>InstanceIndex  : uint
####  <a id="decl-GeometryIndex"></a>GeometryIndex  : uint
####  <a id="decl-PrimitiveIndex"></a>PrimitiveIndex  : uint
####  <a id="decl-HitKind"></a>HitKind  : uint
####  <a id="decl-RayContributionToHitGroupIndex"></a>RayContributionToHitGroupIndex  : uint
####  <a id="decl-MultiplierForGeometryContributionToHitGroupIndex"></a>MultiplierForGeometryContributionToHitGroupIndex  : uint
####  <a id="decl-Ray"></a>Ray  : [RayDesc](../types/raydesc-03/index)
####  <a id="decl-attributes"></a>attributes  : [attr\_t](makehit-04#typeparam-attr_t)
####  <a id="decl-HitGroupRecordIndex"></a>HitGroupRecordIndex  : uint

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


