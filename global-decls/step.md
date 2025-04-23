---
layout: stdlib-reference
---

# step

## Description

Step function.



## Signature 

<pre>
/// Requires Capability Set 1:
<a href="step.md#typeparam-T" class="code_type">T</a> <a href="step.md">step</a>&lt;<a href="step.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="step.md#typeparam-T" class="code_type">T</a> <a href="step.md#decl-y" class="code_param">y</a>,
    <a href="step.md#typeparam-T" class="code_type">T</a> <a href="step.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="step.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 1:
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="step.md#typeparam-T" class="code_type">T</a>, <a href="step.md#decl-N" class="code_var">N</a>&gt; <a href="step.md">step</a>&lt;<a href="step.md#typeparam-T" class="code_type">T</a>, <a href="step.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="step.md#typeparam-T" class="code_type">T</a>, <a href="step.md#decl-N" class="code_var">N</a>&gt; <a href="step.md#decl-y" class="code_param">y</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="step.md#typeparam-T" class="code_type">T</a>, <a href="step.md#decl-N" class="code_var">N</a>&gt; <a href="step.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="step.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 1:
<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="step.md#typeparam-T" class="code_type">T</a>, <a href="step.md#decl-N" class="code_var">N</a>, <a href="step.md#decl-M" class="code_var">M</a>&gt; <a href="step.md">step</a>&lt;<a href="step.md#typeparam-T" class="code_type">T</a>, <a href="step.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="step.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="step.md#typeparam-T" class="code_type">T</a>, <a href="step.md#decl-N" class="code_var">N</a>, <a href="step.md#decl-M" class="code_var">M</a>&gt; <a href="step.md#decl-y" class="code_param">y</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="step.md#typeparam-T" class="code_type">T</a>, <a href="step.md#decl-N" class="code_var">N</a>, <a href="step.md#decl-M" class="code_var">M</a>&gt; <a href="step.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="step.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 2:
<a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="step.md#typeparam-T" class="code_type">T</a>, <a href="step.md#decl-N" class="code_var">N</a>&gt; <a href="step.md">step</a>&lt;<a href="step.md#typeparam-T" class="code_type">T</a>, <a href="step.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="step.md#typeparam-T" class="code_type">T</a>, <a href="step.md#decl-N" class="code_var">N</a>&gt; <a href="step.md#decl-edge" class="code_param">edge</a>,
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="step.md#typeparam-T" class="code_type">T</a>, <a href="step.md#decl-N" class="code_var">N</a>&gt; <a href="step.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="step.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-y"></a>y  : [T](step.md#typeparam-T)
The threshold value.

####  <a id="decl-x"></a>x  : [T](step.md#typeparam-T)
The value to compare against the threshold.

####  <a id="decl-y"></a>y  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The threshold value.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The value to compare against the threshold.

####  <a id="decl-y"></a>y  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The threshold value.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The value to compare against the threshold.

####  <a id="decl-edge"></a>edge  : [CoopVec](../types/coopvec-04/index.md)\<[T](../types/coopvec-04/index.md#typeparam-T), [N](../types/coopvec-04/index.md#decl-N)\>
####  <a id="decl-x"></a>x  : [CoopVec](../types/coopvec-04/index.md)\<[T](../types/coopvec-04/index.md#typeparam-T), [N](../types/coopvec-04/index.md#decl-N)\>
The value to compare against the threshold.


## Return value
0 if <span class='code'><a href="step.md#decl-x" class="code_param">x</a></span> is less than <span class='code'><a href="step.md#decl-y" class="code_param">y</a></span>, and 1 otherwise.


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
