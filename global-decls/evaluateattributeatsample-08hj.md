---
layout: stdlib-reference
---

# EvaluateAttributeAtSample

## Description

Interpolates vertex attribute at the current fragment sample position.



## Signature 

<pre>
<a href="evaluateattributeatsample-08hj.md#typeparam-T" class="code_type">T</a> <a href="evaluateattributeatsample-08hj.md">EvaluateAttributeAtSample</a>&lt;<a href="evaluateattributeatsample-08hj.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="evaluateattributeatsample-08hj.md#typeparam-T" class="code_type">T</a> <a href="evaluateattributeatsample-08hj.md#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href="evaluateattributeatsample-08hj.md#decl-sampleindex" class="code_param">sampleindex</a>)
    <span class='code_keyword'>where</span> <a href="evaluateattributeatsample-08hj.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="evaluateattributeatsample-08hj.md#typeparam-T" class="code_type">T</a>, <a href="evaluateattributeatsample-08hj.md#decl-N" class="code_var">N</a>&gt; <a href="evaluateattributeatsample-08hj.md">EvaluateAttributeAtSample</a>&lt;<a href="evaluateattributeatsample-08hj.md#typeparam-T" class="code_type">T</a>, <a href="evaluateattributeatsample-08hj.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="evaluateattributeatsample-08hj.md#typeparam-T" class="code_type">T</a>, <a href="evaluateattributeatsample-08hj.md#decl-N" class="code_var">N</a>&gt; <a href="evaluateattributeatsample-08hj.md#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href="evaluateattributeatsample-08hj.md#decl-sampleindex" class="code_param">sampleindex</a>)
    <span class='code_keyword'>where</span> <a href="evaluateattributeatsample-08hj.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="evaluateattributeatsample-08hj.md#typeparam-T" class="code_type">T</a>, <a href="evaluateattributeatsample-08hj.md#decl-N" class="code_var">N</a>, <a href="evaluateattributeatsample-08hj.md#decl-M" class="code_var">M</a>&gt; <a href="evaluateattributeatsample-08hj.md">EvaluateAttributeAtSample</a>&lt;<a href="evaluateattributeatsample-08hj.md#typeparam-T" class="code_type">T</a>, <a href="evaluateattributeatsample-08hj.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="evaluateattributeatsample-08hj.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="evaluateattributeatsample-08hj.md#typeparam-T" class="code_type">T</a>, <a href="evaluateattributeatsample-08hj.md#decl-N" class="code_var">N</a>, <a href="evaluateattributeatsample-08hj.md#decl-M" class="code_var">M</a>&gt; <a href="evaluateattributeatsample-08hj.md#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href="evaluateattributeatsample-08hj.md#decl-sampleindex" class="code_param">sampleindex</a>)
    <span class='code_keyword'>where</span> <a href="evaluateattributeatsample-08hj.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](evaluateattributeatsample-08hj.md#typeparam-T)
The vertex attribute to interpolate.

####  <a id="decl-sampleindex"></a>sampleindex  : uint
####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The vertex attribute to interpolate.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The vertex attribute to interpolate.


## Return value
The interpolated attribute value.

## Remarks
<span class='code'><a href="evaluateattributeatsample-08hj.md#decl-x" class="code_param">x</a></span> must be a direct reference to a fragment shader varying input.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

#### glsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

#### spirv
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

Requires capabilities: `SPV_KHR_compute_shader_derivatives`, `spvMeshShadingEXT`.



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
