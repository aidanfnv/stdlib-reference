---
layout: stdlib-reference
---

# GetAttributeAtVertex

## Description

Get the value of a vertex attribute at a specific vertex.

The <span class='code'><a href=".html">GetAttributeAtVertex</a>()</span> function can be used in a fragment shader
to get the value of the given <span class='code'><a href=".html#decl-attribute" class="code_param">attribute</a></span> at the vertex of the primitive
that corresponds to the given <span class='code'><a href=".html#decl-vertexIndex" class="code_param">vertexIndex</a></span>.

Note that the <span class='code'><a href=".html#decl-attribute" class="code_param">attribute</a></span> must have been a declared varying input to
the fragment shader with the <span class='code'>nointerpolation</span> modifier.

This function can be applied to scalars, vectors, and matrices of
built-in scalar types.




## Signature 

<pre>
<a href=".html#typeparam-T" class="code_type">T</a> <a href=".html">GetAttributeAtVertex</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>&gt;(
    <a href=".html#typeparam-T" class="code_type">T</a> <a href=".html#decl-attribute" class="code_param">attribute</a>,
    <span class="code_keyword">uint</span> <a href=".html#decl-vertexIndex" class="code_param">vertexIndex</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : __BuiltinType;

<a href="../../types/vector/index.html" class="code_type">vector</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html">GetAttributeAtVertex</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../../types/vector/index.html" class="code_type">vector</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html#decl-attribute" class="code_param">attribute</a>,
    <span class="code_keyword">uint</span> <a href=".html#decl-vertexIndex" class="code_param">vertexIndex</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : __BuiltinType;

<a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>, <a href=".html#decl-M" class="code_var">M</a>&gt; <a href=".html">GetAttributeAtVertex</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href=".html#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>, <a href=".html#decl-M" class="code_var">M</a>&gt; <a href=".html#decl-attribute" class="code_param">attribute</a>,
    <span class="code_keyword">uint</span> <a href=".html#decl-vertexIndex" class="code_param">vertexIndex</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : __BuiltinType;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: \_\_BuiltinType
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-attribute"></a>attribute  : [T](.html#typeparam-T)
####  <a id="decl-vertexIndex"></a>vertexIndex  : uint
####  <a id="decl-attribute"></a>attribute  : [vector](../../types/vector/index.html)\<[T](../../types/vector/index.html#typeparam-T), [N](../../types/vector/index.html#decl-N)\>
####  <a id="decl-attribute"></a>attribute  : [matrix](../../types/matrix/index.html)\<[T](../../types/matrix/t-0.html), [N](../../types/matrix/index.html#decl-N), [M](../../types/matrix/index.html#decl-M)\>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in `fragment` stage only.

#### glsl
Available in `fragment` stage only.

#### spirv
Available in `fragment` stage only.

Requires capability: `spvFragmentBarycentricKHR`.


