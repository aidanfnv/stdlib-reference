---
layout: stdlib-reference
---

# nextafter

## Description





## Signature 

<pre>
<a href="nextafter.html#typeparam-T" class="code_type">T</a> <a href="nextafter.html">nextafter</a>&lt;<a href="nextafter.html#typeparam-T" class="code_type">T</a>&gt;(
    <a href="nextafter.html#typeparam-T" class="code_type">T</a> <a href="nextafter.html#decl-x" class="code_param">x</a>,
    <a href="nextafter.html#typeparam-T" class="code_type">T</a> <a href="nextafter.html#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="nextafter.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index.html" class="code_type">vector</a>&lt;<a href="nextafter.html#typeparam-T" class="code_type">T</a>, <a href="nextafter.html#decl-N" class="code_var">N</a>&gt; <a href="nextafter.html">nextafter</a>&lt;<a href="nextafter.html#typeparam-T" class="code_type">T</a>, <span class="code_keyword">int</span> <a href="nextafter.html#decl-N" class="code_var">N</a>&gt;(
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<a href="nextafter.html#typeparam-T" class="code_type">T</a>, <a href="nextafter.html#decl-N" class="code_var">N</a>&gt; <a href="nextafter.html#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<a href="nextafter.html#typeparam-T" class="code_type">T</a>, <a href="nextafter.html#decl-N" class="code_var">N</a>&gt; <a href="nextafter.html#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="nextafter.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.html)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](nextafter.html#typeparam-T)
####  <a id="decl-y"></a>y  : [T](nextafter.html#typeparam-T)
####  <a id="decl-x"></a>x  : [vector](../types/vector/index.html)\<[T](../types/vector/index.html#typeparam-T), [N](../types/vector/index.html#decl-N)\>
####  <a id="decl-y"></a>y  : [vector](../types/vector/index.html)\<[T](../types/vector/index.html#typeparam-T), [N](../types/vector/index.html#decl-N)\>

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



