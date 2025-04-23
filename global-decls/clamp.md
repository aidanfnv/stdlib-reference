---
layout: stdlib-reference
---

# clamp

## Description

Clamp. Returns the specified value clamped to the specified minimum and maximum bounds.



## Signature 

<pre>
/// Requires Capability Set 1:
<a href="clamp.md#typeparam-T" class="code_type">T</a> <a href="clamp.md">clamp</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="clamp.md#typeparam-T" class="code_type">T</a> <a href="clamp.md#decl-x" class="code_param">x</a>,
    <a href="clamp.md#typeparam-T" class="code_type">T</a> <a href="clamp.md#decl-minBound" class="code_param">minBound</a>,
    <a href="clamp.md#typeparam-T" class="code_type">T</a> <a href="clamp.md#decl-maxBound" class="code_param">maxBound</a>)
    <span class='code_keyword'>where</span> <a href="clamp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

/// Requires Capability Set 1:
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md">clamp</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md#decl-minBound" class="code_param">minBound</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md#decl-maxBound" class="code_param">maxBound</a>)
    <span class='code_keyword'>where</span> <a href="clamp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

/// Requires Capability Set 1:
<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>, <a href="clamp.md#decl-M" class="code_var">M</a>&gt; <a href="clamp.md">clamp</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="clamp.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>, <a href="clamp.md#decl-M" class="code_var">M</a>&gt; <a href="clamp.md#decl-x" class="code_param">x</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>, <a href="clamp.md#decl-M" class="code_var">M</a>&gt; <a href="clamp.md#decl-minBound" class="code_param">minBound</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>, <a href="clamp.md#decl-M" class="code_var">M</a>&gt; <a href="clamp.md#decl-maxBound" class="code_param">maxBound</a>)
    <span class='code_keyword'>where</span> <a href="clamp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

/// Requires Capability Set 1:
<a href="clamp.md#typeparam-T" class="code_type">T</a> <a href="clamp.md">clamp</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="clamp.md#typeparam-T" class="code_type">T</a> <a href="clamp.md#decl-x" class="code_param">x</a>,
    <a href="clamp.md#typeparam-T" class="code_type">T</a> <a href="clamp.md#decl-minBound" class="code_param">minBound</a>,
    <a href="clamp.md#typeparam-T" class="code_type">T</a> <a href="clamp.md#decl-maxBound" class="code_param">maxBound</a>)
    <span class='code_keyword'>where</span> <a href="clamp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 1:
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md">clamp</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md#decl-minBound" class="code_param">minBound</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md#decl-maxBound" class="code_param">maxBound</a>)
    <span class='code_keyword'>where</span> <a href="clamp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 1:
<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>, <a href="clamp.md#decl-M" class="code_var">M</a>&gt; <a href="clamp.md">clamp</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="clamp.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>, <a href="clamp.md#decl-M" class="code_var">M</a>&gt; <a href="clamp.md#decl-x" class="code_param">x</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>, <a href="clamp.md#decl-M" class="code_var">M</a>&gt; <a href="clamp.md#decl-minBound" class="code_param">minBound</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>, <a href="clamp.md#decl-M" class="code_var">M</a>&gt; <a href="clamp.md#decl-maxBound" class="code_param">maxBound</a>)
    <span class='code_keyword'>where</span> <a href="clamp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 2:
<a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md">clamp</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md#decl-x" class="code_param">x</a>,
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md#decl-minVal" class="code_param">minVal</a>,
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md#decl-maxVal" class="code_param">maxVal</a>)
    <span class='code_keyword'>where</span> <a href="clamp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 2:
<a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md">clamp</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md#decl-x" class="code_param">x</a>,
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md#decl-minVal" class="code_param">minVal</a>,
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="clamp.md#typeparam-T" class="code_type">T</a>, <a href="clamp.md#decl-N" class="code_var">N</a>&gt; <a href="clamp.md#decl-maxVal" class="code_param">maxVal</a>)
    <span class='code_keyword'>where</span> <a href="clamp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinIntegerType](../interfaces/0_builtinintegertype-029g/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int
####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)

## Parameters

####  <a id="decl-x"></a>x  : [T](clamp.md#typeparam-T)
The value to clamp.

####  <a id="decl-minBound"></a>minBound  : [T](clamp.md#typeparam-T)
The minimum bound.

####  <a id="decl-maxBound"></a>maxBound  : [T](clamp.md#typeparam-T)
The maximum bound.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The value to clamp.

####  <a id="decl-minBound"></a>minBound  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The minimum bound.

####  <a id="decl-maxBound"></a>maxBound  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The maximum bound.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The value to clamp.

####  <a id="decl-minBound"></a>minBound  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The minimum bound.

####  <a id="decl-maxBound"></a>maxBound  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The maximum bound.

####  <a id="decl-x"></a>x  : [CoopVec](../types/coopvec-04/index.md)\<[T](../types/coopvec-04/index.md#typeparam-T), [N](../types/coopvec-04/index.md#decl-N)\>
The value to clamp.

####  <a id="decl-minVal"></a>minVal  : [CoopVec](../types/coopvec-04/index.md)\<[T](../types/coopvec-04/index.md#typeparam-T), [N](../types/coopvec-04/index.md#decl-N)\>
####  <a id="decl-maxVal"></a>maxVal  : [CoopVec](../types/coopvec-04/index.md)\<[T](../types/coopvec-04/index.md#typeparam-T), [N](../types/coopvec-04/index.md#decl-N)\>

## Return value
The clamped value.


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
      const href = link.getAttribute('href');
      if (href && href.includes('.md')) {
        // This regex will handle .md links with or without fragment identifiers or query parameters
        link.href = link.href.replace(/(.+)\.md(#[^?]*)?(\?.*)?$/, '$1.html$2$3');
      }
    });
  });
}
</script>
