---
layout: stdlib-reference
---

# fma

## Description

Fused multiply-add.



## Signature 

<pre>
/// Requires Capability Set 1:
<a href="fma.md#typeparam-T" class="code_type">T</a> <a href="fma.md">fma</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="fma.md#typeparam-T" class="code_type">T</a> <a href="fma.md#decl-a" class="code_param">a</a>,
    <a href="fma.md#typeparam-T" class="code_type">T</a> <a href="fma.md#decl-b" class="code_param">b</a>,
    <a href="fma.md#typeparam-T" class="code_type">T</a> <a href="fma.md#decl-c" class="code_param">c</a>)
    <span class='code_keyword'>where</span> <a href="fma.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 1:
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>&gt; <a href="fma.md">fma</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>&gt; <a href="fma.md#decl-a" class="code_param">a</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>&gt; <a href="fma.md#decl-b" class="code_param">b</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>&gt; <a href="fma.md#decl-c" class="code_param">c</a>)
    <span class='code_keyword'>where</span> <a href="fma.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 1:
<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>, <a href="fma.md#decl-M" class="code_var">M</a>&gt; <a href="fma.md">fma</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="fma.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>, <a href="fma.md#decl-M" class="code_var">M</a>&gt; <a href="fma.md#decl-a" class="code_param">a</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>, <a href="fma.md#decl-M" class="code_var">M</a>&gt; <a href="fma.md#decl-b" class="code_param">b</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>, <a href="fma.md#decl-M" class="code_var">M</a>&gt; <a href="fma.md#decl-c" class="code_param">c</a>)
    <span class='code_keyword'>where</span> <a href="fma.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 2:
<a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>&gt; <a href="fma.md">fma</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>&gt; <a href="fma.md#decl-a" class="code_param">a</a>,
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>&gt; <a href="fma.md#decl-b" class="code_param">b</a>,
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="fma.md#typeparam-T" class="code_type">T</a>, <a href="fma.md#decl-N" class="code_var">N</a>&gt; <a href="fma.md#decl-c" class="code_param">c</a>)
    <span class='code_keyword'>where</span> <a href="fma.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-a"></a>a  : [T](fma.md#typeparam-T)
The first value to multiply.

####  <a id="decl-b"></a>b  : [T](fma.md#typeparam-T)
The second value to multiply.

####  <a id="decl-c"></a>c  : [T](fma.md#typeparam-T)
The value to add to the product of <span class='code'><a href="fma.md#decl-a" class="code_param">a</a></span> and <span class='code'><a href="fma.md#decl-b" class="code_param">b</a></span>.

####  <a id="decl-a"></a>a  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The first value to multiply.

####  <a id="decl-b"></a>b  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The second value to multiply.

####  <a id="decl-c"></a>c  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The value to add to the product of <span class='code'><a href="fma.md#decl-a" class="code_param">a</a></span> and <span class='code'><a href="fma.md#decl-b" class="code_param">b</a></span>.

####  <a id="decl-a"></a>a  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The first value to multiply.

####  <a id="decl-b"></a>b  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The second value to multiply.

####  <a id="decl-c"></a>c  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The value to add to the product of <span class='code'><a href="fma.md#decl-a" class="code_param">a</a></span> and <span class='code'><a href="fma.md#decl-b" class="code_param">b</a></span>.

####  <a id="decl-a"></a>a  : [CoopVec](../types/coopvec-04/index.md)\<[T](../types/coopvec-04/index.md#typeparam-T), [N](../types/coopvec-04/index.md#decl-N)\>
The first value to multiply.

####  <a id="decl-b"></a>b  : [CoopVec](../types/coopvec-04/index.md)\<[T](../types/coopvec-04/index.md#typeparam-T), [N](../types/coopvec-04/index.md#decl-N)\>
The second value to multiply.

####  <a id="decl-c"></a>c  : [CoopVec](../types/coopvec-04/index.md)\<[T](../types/coopvec-04/index.md#typeparam-T), [N](../types/coopvec-04/index.md#decl-N)\>
The value to add to the product of <span class='code'><a href="fma.md#decl-a" class="code_param">a</a></span> and <span class='code'><a href="fma.md#decl-b" class="code_param">b</a></span>.


## Return value
The result of <span class='code'><a href="fma.md#decl-a" class="code_param">a</a>*<a href="fma.md#decl-b" class="code_param">b</a>+<a href="fma.md#decl-c" class="code_param">c</a></span>.


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
