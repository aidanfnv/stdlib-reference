---
layout: stdlib-reference
---

# fdim

## Description

Computes <span class='code'><a href="max.md">max</a>(0, <a href="max.md#decl-x" class="code_param">x</a>-<a href="max.md#decl-y" class="code_param">y</a>)</span>.



## Signature 

<pre>
<a href="fdim.md#typeparam-T" class="code_type">T</a> <a href="fdim.md">fdim</a>&lt;<a href="fdim.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="fdim.md#typeparam-T" class="code_type">T</a> <a href="fdim.md#decl-x" class="code_param">x</a>,
    <a href="fdim.md#typeparam-T" class="code_type">T</a> <a href="fdim.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="fdim.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="fdim.md#typeparam-T" class="code_type">T</a>, <a href="fdim.md#decl-N" class="code_var">N</a>&gt; <a href="fdim.md">fdim</a>&lt;<a href="fdim.md#typeparam-T" class="code_type">T</a>, <a href="fdim.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="fdim.md#typeparam-T" class="code_type">T</a>, <a href="fdim.md#decl-N" class="code_var">N</a>&gt; <a href="fdim.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="fdim.md#typeparam-T" class="code_type">T</a>, <a href="fdim.md#decl-N" class="code_var">N</a>&gt; <a href="fdim.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="fdim.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](fdim.md#typeparam-T)
The first value.

####  <a id="decl-y"></a>y  : [T](fdim.md#typeparam-T)
The second value.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The first value.

####  <a id="decl-y"></a>y  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The second value.


## Return value
The result of <span class='code'><a href="max.md">max</a>(0, <a href="max.md#decl-x" class="code_param">x</a>-<a href="max.md#decl-y" class="code_param">y</a>)</span>.


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

#### spirv
Available in all stages.




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
