---
layout: stdlib-reference
---

# min

## Description

Minimum.



## Signature 

<pre>
/// Requires Capability Set 1:
<a href="min.md#typeparam-T" class="code_type">T</a> <a href="min.md">min</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="min.md#typeparam-T" class="code_type">T</a> <a href="min.md#decl-x" class="code_param">x</a>,
    <a href="min.md#typeparam-T" class="code_type">T</a> <a href="min.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="min.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

/// Requires Capability Set 1:
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>&gt; <a href="min.md">min</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>&gt; <a href="min.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>&gt; <a href="min.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="min.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

/// Requires Capability Set 1:
<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>, <a href="min.md#decl-M" class="code_var">M</a>&gt; <a href="min.md">min</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="min.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>, <a href="min.md#decl-M" class="code_var">M</a>&gt; <a href="min.md#decl-x" class="code_param">x</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>, <a href="min.md#decl-M" class="code_var">M</a>&gt; <a href="min.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="min.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

/// Requires Capability Set 1:
<a href="min.md#typeparam-T" class="code_type">T</a> <a href="min.md">min</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="min.md#typeparam-T" class="code_type">T</a> <a href="min.md#decl-x" class="code_param">x</a>,
    <a href="min.md#typeparam-T" class="code_type">T</a> <a href="min.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="min.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 1:
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>&gt; <a href="min.md">min</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>&gt; <a href="min.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>&gt; <a href="min.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="min.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 1:
<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>, <a href="min.md#decl-M" class="code_var">M</a>&gt; <a href="min.md">min</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="min.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>, <a href="min.md#decl-M" class="code_var">M</a>&gt; <a href="min.md#decl-x" class="code_param">x</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>, <a href="min.md#decl-M" class="code_var">M</a>&gt; <a href="min.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="min.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 2:
<a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>&gt; <a href="min.md">min</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>&gt; <a href="min.md#decl-x" class="code_param">x</a>,
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>&gt; <a href="min.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="min.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 2:
<a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>&gt; <a href="min.md">min</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>&gt; <a href="min.md#decl-x" class="code_param">x</a>,
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="min.md#typeparam-T" class="code_type">T</a>, <a href="min.md#decl-N" class="code_var">N</a>&gt; <a href="min.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="min.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinIntegerType](../interfaces/0_builtinintegertype-029g/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int
####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)

## Parameters

####  <a id="decl-x"></a>x  : [T](min.md#typeparam-T)
The first value to compare.

####  <a id="decl-y"></a>y  : [T](min.md#typeparam-T)
The second value to compare.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The first value to compare.

####  <a id="decl-y"></a>y  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The second value to compare.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The first value to compare.

####  <a id="decl-y"></a>y  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The second value to compare.

####  <a id="decl-x"></a>x  : [CoopVec](../types/coopvec-04/index.md)\<[T](../types/coopvec-04/index.md#typeparam-T), [N](../types/coopvec-04/index.md#decl-N)\>
The first value to compare.

####  <a id="decl-y"></a>y  : [CoopVec](../types/coopvec-04/index.md)\<[T](../types/coopvec-04/index.md#typeparam-T), [N](../types/coopvec-04/index.md#decl-N)\>
The second value to compare.


## Return value
The smaller of the two values, element-wise if vector typed.

## Remarks
For HLSL, GLSL, and metal targets, this is implemented with the min() intrinsic.
For SPIR-V, it is implemented with the UMin or SMin instruction, depending on the signedness of the type.


## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### wgsl
Available in all stages.

#### spirv
Available in all stages.


### Capability Set 2

Defined for the following targets:

#### hlsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvCooperativeVectorNV`.



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
