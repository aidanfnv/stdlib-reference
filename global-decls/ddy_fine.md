---
layout: stdlib-reference
---

# ddy\_fine

## Description

Take the fine partial derivative of <span class='code'><a href=".html#decl-p" class="code_param">p</a></span> with respect to y in screen space.



## Signature 

<pre>
<a href=".html#typeparam-T" class="code_type">T</a> <a href=".html">ddy_fine</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>&gt;(<a href=".html#typeparam-T" class="code_type">T</a> <a href=".html#decl-p" class="code_param">p</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../../types/vector/index.html" class="code_type">vector</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html">ddy_fine</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../../types/vector/index.html" class="code_type">vector</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html#decl-p" class="code_param">p</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>, <a href=".html#decl-M" class="code_var">M</a>&gt; <a href=".html">ddy_fine</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href=".html#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>, <a href=".html#decl-M" class="code_var">M</a>&gt; <a href=".html#decl-p" class="code_param">p</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../../interfaces/0_builtinfloatingpointtype-029hm/index.html)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-p"></a>p  : [T](.html#typeparam-T)
The value to take partial derivative for.

####  <a id="decl-p"></a>p  : [vector](../../types/vector/index.html)\<[T](../../types/vector/index.html#typeparam-T), [N](../../types/vector/index.html#decl-N)\>
The value to take partial derivative for.

####  <a id="decl-p"></a>p  : [matrix](../../types/matrix/index.html)\<[T](../../types/matrix/t-0.html), [N](../../types/matrix/index.html#decl-N), [M](../../types/matrix/index.html#decl-M)\>
The value to take partial derivative for.


## Return value
The partial derivative of <span class='code'><a href=".html#decl-p" class="code_param">p</a></span>.

## Remarks
For SPIR-V, this function maps to <span class='code'>OpDPdyFine</span>.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

#### glsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

#### spirv
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

Requires capabilities: `SPV_KHR_compute_shader_derivatives`, `spvMeshShadingEXT`.


