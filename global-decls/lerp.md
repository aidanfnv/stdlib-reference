---
layout: stdlib-reference
---

# lerp

## Description

Computes linear interpolation.



## Signature 

<pre>
<a href="lerp.md#typeparam-T" class="code_type">T</a> <a href="lerp.md">lerp</a>&lt;<a href="lerp.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="lerp.md#typeparam-T" class="code_type">T</a> <a href="lerp.md#decl-x" class="code_param">x</a>,
    <a href="lerp.md#typeparam-T" class="code_type">T</a> <a href="lerp.md#decl-y" class="code_param">y</a>,
    <a href="lerp.md#typeparam-T" class="code_type">T</a> <a href="lerp.md#decl-s" class="code_param">s</a>)
    <span class='code_keyword'>where</span> <a href="lerp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="lerp.md#typeparam-T" class="code_type">T</a>, <a href="lerp.md#decl-N" class="code_var">N</a>&gt; <a href="lerp.md">lerp</a>&lt;<a href="lerp.md#typeparam-T" class="code_type">T</a>, <a href="lerp.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="lerp.md#typeparam-T" class="code_type">T</a>, <a href="lerp.md#decl-N" class="code_var">N</a>&gt; <a href="lerp.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="lerp.md#typeparam-T" class="code_type">T</a>, <a href="lerp.md#decl-N" class="code_var">N</a>&gt; <a href="lerp.md#decl-y" class="code_param">y</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="lerp.md#typeparam-T" class="code_type">T</a>, <a href="lerp.md#decl-N" class="code_var">N</a>&gt; <a href="lerp.md#decl-s" class="code_param">s</a>)
    <span class='code_keyword'>where</span> <a href="lerp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="lerp.md#typeparam-T" class="code_type">T</a>, <a href="lerp.md#decl-N" class="code_var">N</a>, <a href="lerp.md#decl-M" class="code_var">M</a>&gt; <a href="lerp.md">lerp</a>&lt;<a href="lerp.md#typeparam-T" class="code_type">T</a>, <a href="lerp.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="lerp.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="lerp.md#typeparam-T" class="code_type">T</a>, <a href="lerp.md#decl-N" class="code_var">N</a>, <a href="lerp.md#decl-M" class="code_var">M</a>&gt; <a href="lerp.md#decl-x" class="code_param">x</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="lerp.md#typeparam-T" class="code_type">T</a>, <a href="lerp.md#decl-N" class="code_var">N</a>, <a href="lerp.md#decl-M" class="code_var">M</a>&gt; <a href="lerp.md#decl-y" class="code_param">y</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="lerp.md#typeparam-T" class="code_type">T</a>, <a href="lerp.md#decl-N" class="code_var">N</a>, <a href="lerp.md#decl-M" class="code_var">M</a>&gt; <a href="lerp.md#decl-s" class="code_param">s</a>)
    <span class='code_keyword'>where</span> <a href="lerp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](lerp.md#typeparam-T)
The starting value.

####  <a id="decl-y"></a>y  : [T](lerp.md#typeparam-T)
The ending value.

####  <a id="decl-s"></a>s  : [T](lerp.md#typeparam-T)
The interpolation factor.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The starting value.

####  <a id="decl-y"></a>y  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The ending value.

####  <a id="decl-s"></a>s  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The interpolation factor.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The starting value.

####  <a id="decl-y"></a>y  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The ending value.

####  <a id="decl-s"></a>s  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The interpolation factor.


## Return value
Returns <span class='code'><a href="lerp.md#decl-x" class="code_param">x</a>+(<a href="lerp.md#decl-y" class="code_param">y</a>-<a href="lerp.md#decl-x" class="code_param">x</a>)*<a href="lerp.md#decl-s" class="code_param">s</a></span>.



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
