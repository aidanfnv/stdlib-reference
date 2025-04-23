---
layout: stdlib-reference
---

# fwidth

## Description

Texture filter width.
Calculates the sum abs(ddx(<span class='code'><a href="fwidth.md#decl-p" class="code_param">p</a></span>)) + abs(ddy(<span class='code'><a href="fwidth.md#decl-p" class="code_param">p</a></span>)).



## Signature 

<pre>
/// Requires Capability Set 1:
<a href="fwidth.md#typeparam-T" class="code_type">T</a> <a href="fwidth.md">fwidth</a>&lt;<a href="fwidth.md#typeparam-T" class="code_type">T</a>&gt;(<a href="fwidth.md#typeparam-T" class="code_type">T</a> <a href="fwidth.md#decl-p" class="code_param">p</a>)
    <span class='code_keyword'>where</span> <a href="fwidth.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 2:
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="fwidth.md#typeparam-T" class="code_type">T</a>, <a href="fwidth.md#decl-N" class="code_var">N</a>&gt; <a href="fwidth.md">fwidth</a>&lt;<a href="fwidth.md#typeparam-T" class="code_type">T</a>, <a href="fwidth.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="fwidth.md#typeparam-T" class="code_type">T</a>, <a href="fwidth.md#decl-N" class="code_var">N</a>&gt; <a href="fwidth.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="fwidth.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 3:
<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="fwidth.md#typeparam-T" class="code_type">T</a>, <a href="fwidth.md#decl-N" class="code_var">N</a>, <a href="fwidth.md#decl-M" class="code_var">M</a>&gt; <a href="fwidth.md">fwidth</a>&lt;<a href="fwidth.md#typeparam-T" class="code_type">T</a>, <a href="fwidth.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="fwidth.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="fwidth.md#typeparam-T" class="code_type">T</a>, <a href="fwidth.md#decl-N" class="code_var">N</a>, <a href="fwidth.md#decl-M" class="code_var">M</a>&gt; <a href="fwidth.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="fwidth.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-p"></a>p  : [T](fwidth.md#typeparam-T)
The value to sum x and y partial derivative magnitudes for.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>

## Return value
The sum of abs(ddx(<span class='code'><a href="fwidth.md#decl-p" class="code_param">p</a></span>)) and abs(ddy(<span class='code'><a href="fwidth.md#decl-p" class="code_param">p</a></span>)).

## Remarks
For SPIR-V, this function maps to <span class='code'>OpFwidth</span>.


## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

#### glsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

#### metal
Available in `fragment` stage only.

#### wgsl
Available in `fragment` stage only.

#### spirv
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

Requires capabilities: `SPV_KHR_compute_shader_derivatives`, `spvMeshShadingEXT`.

### Capability Set 2

Defined for the following targets:

#### hlsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

#### glsl
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

#### wgsl
Available in `fragment` stage only.

#### spirv
Available in stages: `amplification`, `fragment`, `compute`, `mesh`, `miss`, `callable`, `raygen`, `intersection`, `anyhit`, `closesthit`.

Requires capabilities: `SPV_KHR_compute_shader_derivatives`, `spvMeshShadingEXT`.

### Capability Set 3

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
