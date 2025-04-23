---
layout: stdlib-reference
---

# smoothstep

## Description

Smooth step (Hermite interpolation).



## Signature 

<pre>
<a href="smoothstep.md#typeparam-T" class="code_type">T</a> <a href="smoothstep.md">smoothstep</a>&lt;<a href="smoothstep.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="smoothstep.md#typeparam-T" class="code_type">T</a> <a href="smoothstep.md#decl-min" class="code_param">min</a>,
    <a href="smoothstep.md#typeparam-T" class="code_type">T</a> <a href="smoothstep.md#decl-max" class="code_param">max</a>,
    <a href="smoothstep.md#typeparam-T" class="code_type">T</a> <a href="smoothstep.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="smoothstep.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="smoothstep.md#typeparam-T" class="code_type">T</a>, <a href="smoothstep.md#decl-N" class="code_var">N</a>&gt; <a href="smoothstep.md">smoothstep</a>&lt;<a href="smoothstep.md#typeparam-T" class="code_type">T</a>, <a href="smoothstep.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="smoothstep.md#typeparam-T" class="code_type">T</a>, <a href="smoothstep.md#decl-N" class="code_var">N</a>&gt; <a href="smoothstep.md#decl-min" class="code_param">min</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="smoothstep.md#typeparam-T" class="code_type">T</a>, <a href="smoothstep.md#decl-N" class="code_var">N</a>&gt; <a href="smoothstep.md#decl-max" class="code_param">max</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="smoothstep.md#typeparam-T" class="code_type">T</a>, <a href="smoothstep.md#decl-N" class="code_var">N</a>&gt; <a href="smoothstep.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="smoothstep.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="smoothstep.md#typeparam-T" class="code_type">T</a>, <a href="smoothstep.md#decl-N" class="code_var">N</a>, <a href="smoothstep.md#decl-M" class="code_var">M</a>&gt; <a href="smoothstep.md">smoothstep</a>&lt;<a href="smoothstep.md#typeparam-T" class="code_type">T</a>, <a href="smoothstep.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="smoothstep.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="smoothstep.md#typeparam-T" class="code_type">T</a>, <a href="smoothstep.md#decl-N" class="code_var">N</a>, <a href="smoothstep.md#decl-M" class="code_var">M</a>&gt; <a href="smoothstep.md#decl-min" class="code_param">min</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="smoothstep.md#typeparam-T" class="code_type">T</a>, <a href="smoothstep.md#decl-N" class="code_var">N</a>, <a href="smoothstep.md#decl-M" class="code_var">M</a>&gt; <a href="smoothstep.md#decl-max" class="code_param">max</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="smoothstep.md#typeparam-T" class="code_type">T</a>, <a href="smoothstep.md#decl-N" class="code_var">N</a>, <a href="smoothstep.md#decl-M" class="code_var">M</a>&gt; <a href="smoothstep.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="smoothstep.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-min"></a>min  : [T](smoothstep.md#typeparam-T)
The lower edge of the interpolation range.

####  <a id="decl-max"></a>max  : [T](smoothstep.md#typeparam-T)
The upper edge of the interpolation range.

####  <a id="decl-x"></a>x  : [T](smoothstep.md#typeparam-T)
The value to interpolate.

####  <a id="decl-min"></a>min  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The lower edge of the interpolation range.

####  <a id="decl-max"></a>max  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The upper edge of the interpolation range.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The value to interpolate.

####  <a id="decl-min"></a>min  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The lower edge of the interpolation range.

####  <a id="decl-max"></a>max  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The upper edge of the interpolation range.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The value to interpolate.


## Return value
0 if <span class='code'><a href="smoothstep.md#decl-x" class="code_param">x</a></span> is less than <span class='code'><a href="smoothstep.md#decl-min" class="code_param">min</a></span>, 1 if <span class='code'><a href="smoothstep.md#decl-x" class="code_param">x</a></span> is greater than <span class='code'><a href="smoothstep.md#decl-max" class="code_param">max</a></span>, and a smooth interpolation between 0 and 1 otherwise.


## Availability and Requirements

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
