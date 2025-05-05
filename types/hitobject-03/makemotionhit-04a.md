---
layout: stdlib-reference
---

# HitObject\.MakeMotionHit

## Description

See MakeHit but handles Motion
Currently only supported on VK




## Signature 

<pre>
/// Requires Capability Set 1:
<span class='code_keyword'>static</span> <a href="/stdlib-reference/types/hitobject-03/index" class="code_type">HitObject</a> <a href="/stdlib-reference/types/hitobject-03/index" class="code_type">HitObject</a>.<a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a">MakeMotionHit</a>&lt;<a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#typeparam-attr_t" class="code_type">attr_t</a>&gt;(
    <a href="/stdlib-reference/types/raytracingaccelerationstructure-0am/index" class="code_type">RaytracingAccelerationStructure</a> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-AccelerationStructure" class="code_param">AccelerationStructure</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-InstanceIndex" class="code_param">InstanceIndex</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-GeometryIndex" class="code_param">GeometryIndex</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-PrimitiveIndex" class="code_param">PrimitiveIndex</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-HitKind" class="code_param">HitKind</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-RayContributionToHitGroupIndex" class="code_param">RayContributionToHitGroupIndex</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-MultiplierForGeometryContributionToHitGroupIndex" class="code_param">MultiplierForGeometryContributionToHitGroupIndex</a>,
    <a href="/stdlib-reference/types/raydesc-03/index" class="code_type">RayDesc</a> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-Ray" class="code_param">Ray</a>,
    <span class="code_keyword">float</span> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-CurrentTime" class="code_param">CurrentTime</a>,
    <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#typeparam-attr_t" class="code_type">attr_t</a> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-attributes" class="code_param">attributes</a>);

/// Requires Capability Set 2:
<span class='code_keyword'>static</span> <a href="/stdlib-reference/types/hitobject-03/index" class="code_type">HitObject</a> <a href="/stdlib-reference/types/hitobject-03/index" class="code_type">HitObject</a>.<a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a">MakeMotionHit</a>&lt;<a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#typeparam-attr_t" class="code_type">attr_t</a>&gt;(
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-HitGroupRecordIndex" class="code_param">HitGroupRecordIndex</a>,
    <a href="/stdlib-reference/types/raytracingaccelerationstructure-0am/index" class="code_type">RaytracingAccelerationStructure</a> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-AccelerationStructure" class="code_param">AccelerationStructure</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-InstanceIndex" class="code_param">InstanceIndex</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-GeometryIndex" class="code_param">GeometryIndex</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-PrimitiveIndex" class="code_param">PrimitiveIndex</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-HitKind" class="code_param">HitKind</a>,
    <a href="/stdlib-reference/types/raydesc-03/index" class="code_type">RayDesc</a> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-Ray" class="code_param">Ray</a>,
    <span class="code_keyword">float</span> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-CurrentTime" class="code_param">CurrentTime</a>,
    <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#typeparam-attr_t" class="code_type">attr_t</a> <a href="/stdlib-reference/types/hitobject-03/makemotionhit-04a#decl-attributes" class="code_param">attributes</a>);

</pre>

## Generic Parameters

#### attr\_t {#typeparam-attr_t}

## Parameters

#### AccelerationStructure  : [RaytracingAccelerationStructure](/stdlib-reference/types/raytracingaccelerationstructure-0am/index) {#decl-AccelerationStructure}
#### InstanceIndex  : uint {#decl-InstanceIndex}
#### GeometryIndex  : uint {#decl-GeometryIndex}
#### PrimitiveIndex  : uint {#decl-PrimitiveIndex}
#### HitKind  : uint {#decl-HitKind}
#### RayContributionToHitGroupIndex  : uint {#decl-RayContributionToHitGroupIndex}
#### MultiplierForGeometryContributionToHitGroupIndex  : uint {#decl-MultiplierForGeometryContributionToHitGroupIndex}
#### Ray  : [RayDesc](/stdlib-reference/types/raydesc-03/index) {#decl-Ray}
#### CurrentTime  : float {#decl-CurrentTime}
#### attributes  : [attr\_t](/stdlib-reference/types/hitobject-03/makemotionhit-04a#typeparam-attr_t) {#decl-attributes}
#### HitGroupRecordIndex  : uint {#decl-HitGroupRecordIndex}

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in stages: `raygen`, `closesthit`, `miss`.

Requires capability: `hlsl_nvapi`.
#### glsl
Available in stages: `raygen`, `closesthit`, `miss`.

#### spirv
Available in stages: `raygen`, `closesthit`, `miss`.

Requires capabilities: `spvRayTracingMotionBlurNV`, `spvRayTracingKHR`, `spvShaderInvocationReorderNV`.

### Capability Set 2

Defined for the following targets:

#### glsl
Available in stages: `raygen`, `closesthit`, `miss`.

#### spirv
Available in stages: `raygen`, `closesthit`, `miss`.

Requires capabilities: `spvRayTracingMotionBlurNV`, `spvRayTracingKHR`, `spvShaderInvocationReorderNV`.


