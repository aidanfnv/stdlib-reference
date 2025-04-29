---
layout: stdlib-reference
---

# RaytracingAccelerationStructure\.init

## Description





## Signature 

<pre>
<a href="../types/raytracingaccelerationstructure-0am/index" class="code_type">RaytracingAccelerationStructure</a>.<a href="init">init</a>(uint64_t <a href="init#decl-address" class="code_param">address</a>);

<a href="../types/raytracingaccelerationstructure-0am/index" class="code_type">RaytracingAccelerationStructure</a>.<a href="init">init</a>(__DynamicResource&lt;__DynamicResourceKind.General&gt; <a href="init#decl-res" class="code_param">res</a>);

<a href="../types/raytracingaccelerationstructure-0am/index" class="code_type">RaytracingAccelerationStructure</a>.<a href="init">init</a>(<a href="../types/descriptorhandle-0a/index" class="code_type">DescriptorHandle</a>&lt;<a href="../types/raytracingaccelerationstructure-0am/index" class="code_type">RaytracingAccelerationStructure</a>&gt; <a href="init#decl-bindless" class="code_param">bindless</a>);

</pre>

## Parameters

####  <a id="decl-address"></a>address  : uint64\_t
####  <a id="decl-res"></a>res  : \_\_DynamicResource\<\_\_DynamicResourceKind\.General\>
####  <a id="decl-bindless"></a>bindless  : [DescriptorHandle](../types/descriptorhandle-0a/index)\<[RaytracingAccelerationStructure](../types/raytracingaccelerationstructure-0am/index)\>

## Availability and Requirements

Defined for the following targets:

#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvRayTracingKHR`.


