---
layout: stdlib-reference
---

# ddy\_fine

## Description

Take the fine partial derivative of <span class='code'><a href="ddy_fine.md#decl-p" class="code_param">p</a></span> with respect to y in screen space.



## Signature 

<pre>
<a href="ddy_fine.md#typeparam-T" class="code_type">T</a> <a href="ddy_fine.md">ddy_fine</a>&lt;<a href="ddy_fine.md#typeparam-T" class="code_type">T</a>&gt;(<a href="ddy_fine.md#typeparam-T" class="code_type">T</a> <a href="ddy_fine.md#decl-p" class="code_param">p</a>)
    <span class='code_keyword'>where</span> <a href="ddy_fine.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="ddy_fine.md#typeparam-T" class="code_type">T</a>, <a href="ddy_fine.md#decl-N" class="code_var">N</a>&gt; <a href="ddy_fine.md">ddy_fine</a>&lt;<a href="ddy_fine.md#typeparam-T" class="code_type">T</a>, <a href="ddy_fine.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="ddy_fine.md#typeparam-T" class="code_type">T</a>, <a href="ddy_fine.md#decl-N" class="code_var">N</a>&gt; <a href="ddy_fine.md#decl-p" class="code_param">p</a>)
    <span class='code_keyword'>where</span> <a href="ddy_fine.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="ddy_fine.md#typeparam-T" class="code_type">T</a>, <a href="ddy_fine.md#decl-N" class="code_var">N</a>, <a href="ddy_fine.md#decl-M" class="code_var">M</a>&gt; <a href="ddy_fine.md">ddy_fine</a>&lt;<a href="ddy_fine.md#typeparam-T" class="code_type">T</a>, <a href="ddy_fine.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="ddy_fine.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="ddy_fine.md#typeparam-T" class="code_type">T</a>, <a href="ddy_fine.md#decl-N" class="code_var">N</a>, <a href="ddy_fine.md#decl-M" class="code_var">M</a>&gt; <a href="ddy_fine.md#decl-p" class="code_param">p</a>)
    <span class='code_keyword'>where</span> <a href="ddy_fine.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-p"></a>p  : [T](ddy_fine.md#typeparam-T)
The value to take partial derivative for.

####  <a id="decl-p"></a>p  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The value to take partial derivative for.

####  <a id="decl-p"></a>p  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The value to take partial derivative for.


## Return value
The partial derivative of <span class='code'><a href="ddy_fine.md#decl-p" class="code_param">p</a></span>.

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
