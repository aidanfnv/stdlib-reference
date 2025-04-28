---
layout: stdlib-reference
---

# lerp

## Description

Computes linear interpolation.



## Signature 

<pre>
<a href=".html#typeparam-T" class="code_type">T</a> <a href=".html">lerp</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>&gt;(
    <a href=".html#typeparam-T" class="code_type">T</a> <a href=".html#decl-x" class="code_param">x</a>,
    <a href=".html#typeparam-T" class="code_type">T</a> <a href=".html#decl-y" class="code_param">y</a>,
    <a href=".html#typeparam-T" class="code_type">T</a> <a href=".html#decl-s" class="code_param">s</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../../types/vector/index.html" class="code_type">vector</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html">lerp</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../../types/vector/index.html" class="code_type">vector</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html#decl-x" class="code_param">x</a>,
    <a href="../../types/vector/index.html" class="code_type">vector</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html#decl-y" class="code_param">y</a>,
    <a href="../../types/vector/index.html" class="code_type">vector</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html#decl-s" class="code_param">s</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>, <a href=".html#decl-M" class="code_var">M</a>&gt; <a href=".html">lerp</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href=".html#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>, <a href=".html#decl-M" class="code_var">M</a>&gt; <a href=".html#decl-x" class="code_param">x</a>,
    <a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>, <a href=".html#decl-M" class="code_var">M</a>&gt; <a href=".html#decl-y" class="code_param">y</a>,
    <a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>, <a href=".html#decl-M" class="code_var">M</a>&gt; <a href=".html#decl-s" class="code_param">s</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../../interfaces/0_builtinfloatingpointtype-029hm/index.html)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](.html#typeparam-T)
The starting value.

####  <a id="decl-y"></a>y  : [T](.html#typeparam-T)
The ending value.

####  <a id="decl-s"></a>s  : [T](.html#typeparam-T)
The interpolation factor.

####  <a id="decl-x"></a>x  : [vector](../../types/vector/index.html)\<[T](../../types/vector/index.html#typeparam-T), [N](../../types/vector/index.html#decl-N)\>
The starting value.

####  <a id="decl-y"></a>y  : [vector](../../types/vector/index.html)\<[T](../../types/vector/index.html#typeparam-T), [N](../../types/vector/index.html#decl-N)\>
The ending value.

####  <a id="decl-s"></a>s  : [vector](../../types/vector/index.html)\<[T](../../types/vector/index.html#typeparam-T), [N](../../types/vector/index.html#decl-N)\>
The interpolation factor.

####  <a id="decl-x"></a>x  : [matrix](../../types/matrix/index.html)\<[T](../../types/matrix/t-0.html), [N](../../types/matrix/index.html#decl-N), [M](../../types/matrix/index.html#decl-M)\>
The starting value.

####  <a id="decl-y"></a>y  : [matrix](../../types/matrix/index.html)\<[T](../../types/matrix/t-0.html), [N](../../types/matrix/index.html#decl-N), [M](../../types/matrix/index.html#decl-M)\>
The ending value.

####  <a id="decl-s"></a>s  : [matrix](../../types/matrix/index.html)\<[T](../../types/matrix/t-0.html), [N](../../types/matrix/index.html#decl-N), [M](../../types/matrix/index.html#decl-M)\>
The interpolation factor.


## Return value
Returns <span class='code'><a href=".html#decl-x" class="code_param">x</a>+(<a href=".html#decl-y" class="code_param">y</a>-<a href=".html#decl-x" class="code_param">x</a>)*<a href=".html#decl-s" class="code_param">s</a></span>.


