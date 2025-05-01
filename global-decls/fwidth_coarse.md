---
layout: stdlib-reference
---

# fwidth\_coarse

## Description

Texture filter width (coarse).
Calculates the sum abs(ddx_coarse(<span class='code'><a href="fwidth_coarse.html#decl-p" class="code_param">p</a></span>)) + abs(ddy_coarse(<span class='code'><a href="fwidth_coarse.html#decl-p" class="code_param">p</a></span>)).



## Signature 

<pre>
/// Requires Capability Set 1:
<a href="fwidth_coarse.html#typeparam-T" class="code_type">T</a> <a href="fwidth_coarse.html">fwidth_coarse</a>&lt;<a href="fwidth_coarse.html#typeparam-T" class="code_type">T</a>&gt;(<a href="fwidth_coarse.html#typeparam-T" class="code_type">T</a> <a href="fwidth_coarse.html#decl-p" class="code_param">p</a>)
    <span class='code_keyword'>where</span> <a href="fwidth_coarse.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 1:
<a href="../types/vector/index.html" class="code_type">vector</a>&lt;<a href="fwidth_coarse.html#typeparam-T" class="code_type">T</a>, <a href="fwidth_coarse.html#decl-N" class="code_var">N</a>&gt; <a href="fwidth_coarse.html">fwidth_coarse</a>&lt;<a href="fwidth_coarse.html#typeparam-T" class="code_type">T</a>, <a href="fwidth_coarse.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.html" class="code_type">vector</a>&lt;<a href="fwidth_coarse.html#typeparam-T" class="code_type">T</a>, <a href="fwidth_coarse.html#decl-N" class="code_var">N</a>&gt; <a href="fwidth_coarse.html#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="fwidth_coarse.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 2:
<a href="../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href="fwidth_coarse.html#typeparam-T" class="code_type">T</a>, <a href="fwidth_coarse.html#decl-N" class="code_var">N</a>, <a href="fwidth_coarse.html#decl-M" class="code_var">M</a>&gt; <a href="fwidth_coarse.html">fwidth_coarse</a>&lt;<a href="fwidth_coarse.html#typeparam-T" class="code_type">T</a>, <a href="fwidth_coarse.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="fwidth_coarse.html#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href="fwidth_coarse.html#typeparam-T" class="code_type">T</a>, <a href="fwidth_coarse.html#decl-N" class="code_var">N</a>, <a href="fwidth_coarse.html#decl-M" class="code_var">M</a>&gt; <a href="fwidth_coarse.html#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="fwidth_coarse.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-p"></a>p  : [T](fwidth_coarse#typeparam-T)
The value to sum x and y partial derivative magnitudes for.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index)\<[T](../types/matrix/t-0), [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>

## Return value
The sum of abs(ddx_coarse(<span class='code'><a href="fwidth_coarse.html#decl-p" class="code_param">p</a></span>)) and abs(ddy_coarse(<span class='code'><a href="fwidth_coarse.html#decl-p" class="code_param">p</a></span>)).

## Remarks
For SPIR-V, this function maps to <span class='code'>OpFwidthCoarse</span>.


## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `closesthit`, `raygen`, `intersection`, `anyhit`.

#### glsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `closesthit`, `raygen`, `intersection`, `anyhit`.

#### spirv
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `closesthit`, `raygen`, `intersection`, `anyhit`.

Requires capabilities: `SPV_KHR_compute_shader_derivatives`, `spvMeshShadingEXT`.

### Capability Set 2

Defined for the following targets:

#### hlsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `closesthit`, `raygen`, `intersection`, `anyhit`.

#### glsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `closesthit`, `raygen`, `intersection`, `anyhit`.

#### spirv
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `closesthit`, `raygen`, `intersection`, `anyhit`.

Requires capabilities: `SPV_KHR_compute_shader_derivatives`, `spvMeshShadingEXT`.


