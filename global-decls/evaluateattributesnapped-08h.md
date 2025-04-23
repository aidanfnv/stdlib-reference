---
layout: stdlib-reference
---

# EvaluateAttributeSnapped

## Description

Interpolates vertex attribute at the specified subpixel offset.



## Signature 

<pre>
<a href="evaluateattributesnapped-08h.md#typeparam-T" class="code_type">T</a> <a href="evaluateattributesnapped-08h.md">EvaluateAttributeSnapped</a>&lt;<a href="evaluateattributesnapped-08h.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="evaluateattributesnapped-08h.md#typeparam-T" class="code_type">T</a> <a href="evaluateattributesnapped-08h.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, 2&gt; <a href="evaluateattributesnapped-08h.md#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="evaluateattributesnapped-08h.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="evaluateattributesnapped-08h.md#typeparam-T" class="code_type">T</a>, <a href="evaluateattributesnapped-08h.md#decl-N" class="code_var">N</a>&gt; <a href="evaluateattributesnapped-08h.md">EvaluateAttributeSnapped</a>&lt;<a href="evaluateattributesnapped-08h.md#typeparam-T" class="code_type">T</a>, <a href="evaluateattributesnapped-08h.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="evaluateattributesnapped-08h.md#typeparam-T" class="code_type">T</a>, <a href="evaluateattributesnapped-08h.md#decl-N" class="code_var">N</a>&gt; <a href="evaluateattributesnapped-08h.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, 2&gt; <a href="evaluateattributesnapped-08h.md#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="evaluateattributesnapped-08h.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="evaluateattributesnapped-08h.md#typeparam-T" class="code_type">T</a>, <a href="evaluateattributesnapped-08h.md#decl-N" class="code_var">N</a>, <a href="evaluateattributesnapped-08h.md#decl-M" class="code_var">M</a>&gt; <a href="evaluateattributesnapped-08h.md">EvaluateAttributeSnapped</a>&lt;<a href="evaluateattributesnapped-08h.md#typeparam-T" class="code_type">T</a>, <a href="evaluateattributesnapped-08h.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="evaluateattributesnapped-08h.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="evaluateattributesnapped-08h.md#typeparam-T" class="code_type">T</a>, <a href="evaluateattributesnapped-08h.md#decl-N" class="code_var">N</a>, <a href="evaluateattributesnapped-08h.md#decl-M" class="code_var">M</a>&gt; <a href="evaluateattributesnapped-08h.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, 2&gt; <a href="evaluateattributesnapped-08h.md#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="evaluateattributesnapped-08h.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](evaluateattributesnapped-08h.md#typeparam-T)
The vertex attribute to interpolate.

####  <a id="decl-offset"></a>offset  : [vector](../types/vector/index.md)\<int, 2\>
The subpixel offset. Each component is a 4-bit signed integer in range [-8, 7].

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The vertex attribute to interpolate.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The vertex attribute to interpolate.


## Return value
The interpolated attribute value.

## Remarks
<span class='code'><a href="evaluateattributesnapped-08h.md#decl-x" class="code_param">x</a></span> must be a direct reference to a fragment shader varying input.

The valid values of each component of <span class='code'><a href="evaluateattributesnapped-08h.md#decl-offset" class="code_param">offset</a></span> are:

- 1000 = -0.5f (-8 / 16)
- 1001 = -0.4375f (-7 / 16)
- 1010 = -0.375f (-6 / 16)
- 1011 = -0.3125f (-5 / 16)
- 1100 = -0.25f (-4 / 16)
- 1101 = -0.1875f (-3 / 16)
- 1110 = -0.125f (-2 / 16)
- 1111 = -0.0625f (-1 / 16)
- 0000 = 0.0f ( 0 / 16)
- 0001 = 0.0625f ( 1 / 16)
- 0010 = 0.125f ( 2 / 16)
- 0011 = 0.1875f ( 3 / 16)
- 0100 = 0.25f ( 4 / 16)
- 0101 = 0.3125f ( 5 / 16)
- 0110 = 0.375f ( 6 / 16)
- 0111 = 0.4375f ( 7 / 16)


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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
