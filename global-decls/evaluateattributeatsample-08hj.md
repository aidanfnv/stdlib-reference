---
layout: stdlib-reference
---

# EvaluateAttributeAtSample

## Description

Interpolates vertex attribute at the current fragment sample position.



## Signature 

<pre>
<a href=".html#typeparam-T" class="code_type">T</a> <a href=".html">EvaluateAttributeAtSample</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>&gt;(
    <a href=".html#typeparam-T" class="code_type">T</a> <a href=".html#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href=".html#decl-sampleindex" class="code_param">sampleindex</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

<a href="../../types/vector/index.html" class="code_type">vector</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html">EvaluateAttributeAtSample</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../../types/vector/index.html" class="code_type">vector</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href=".html#decl-sampleindex" class="code_param">sampleindex</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

<a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>, <a href=".html#decl-M" class="code_var">M</a>&gt; <a href=".html">EvaluateAttributeAtSample</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href=".html#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>, <a href=".html#decl-M" class="code_var">M</a>&gt; <a href=".html#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href=".html#decl-sampleindex" class="code_param">sampleindex</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../../interfaces/0_builtinarithmetictype-029j/index.html)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](.html#typeparam-T)
The vertex attribute to interpolate.

####  <a id="decl-sampleindex"></a>sampleindex  : uint
####  <a id="decl-x"></a>x  : [vector](../../types/vector/index.html)\<[T](../../types/vector/index.html#typeparam-T), [N](../../types/vector/index.html#decl-N)\>
The vertex attribute to interpolate.

####  <a id="decl-x"></a>x  : [matrix](../../types/matrix/index.html)\<[T](../../types/matrix/t-0.html), [N](../../types/matrix/index.html#decl-N), [M](../../types/matrix/index.html#decl-M)\>
The vertex attribute to interpolate.


## Return value
The interpolated attribute value.

## Remarks
<span class='code'><a href=".html#decl-x" class="code_param">x</a></span> must be a direct reference to a fragment shader varying input.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

#### glsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

#### spirv
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

Requires capabilities: `SPV_KHR_compute_shader_derivatives`, `spvMeshShadingEXT`.


