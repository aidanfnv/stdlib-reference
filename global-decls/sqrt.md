---
layout: stdlib-reference
---

# sqrt

## Description

Compute the square root of <span class='code'><a href="sqrt.html#decl-x" class="code_param">x</a></span>.



## Signature 

<pre>
<a href="sqrt.html#typeparam-T" class="code_type">T</a> <a href="sqrt.html">sqrt</a>&lt;<a href="sqrt.html#typeparam-T" class="code_type">T</a>&gt;(<a href="sqrt.html#typeparam-T" class="code_type">T</a> <a href="sqrt.html#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="sqrt.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index.html" class="code_type">vector</a>&lt;<a href="sqrt.html#typeparam-T" class="code_type">T</a>, <a href="sqrt.html#decl-N" class="code_var">N</a>&gt; <a href="sqrt.html">sqrt</a>&lt;<a href="sqrt.html#typeparam-T" class="code_type">T</a>, <a href="sqrt.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.html" class="code_type">vector</a>&lt;<a href="sqrt.html#typeparam-T" class="code_type">T</a>, <a href="sqrt.html#decl-N" class="code_var">N</a>&gt; <a href="sqrt.html#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="sqrt.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href="sqrt.html#typeparam-T" class="code_type">T</a>, <a href="sqrt.html#decl-N" class="code_var">N</a>, <a href="sqrt.html#decl-M" class="code_var">M</a>&gt; <a href="sqrt.html">sqrt</a>&lt;<a href="sqrt.html#typeparam-T" class="code_type">T</a>, <a href="sqrt.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="sqrt.html#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index.html" class="code_type">matrix</a>&lt;<a href="sqrt.html#typeparam-T" class="code_type">T</a>, <a href="sqrt.html#decl-N" class="code_var">N</a>, <a href="sqrt.html#decl-M" class="code_var">M</a>&gt; <a href="sqrt.html#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="sqrt.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.html)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](sqrt.html#typeparam-T)
The value to compute the square root of.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.html)\<[T](../types/vector/index.html#typeparam-T), [N](../types/vector/index.html#decl-N)\>
The value to compute the square root of.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.html)\<[T](.html), [N](../types/matrix/index.html#decl-N), [M](../types/matrix/index.html#decl-M)\>
The value to compute the square root of.


## Return value
The square root of <span class='code'><a href="sqrt.html#decl-x" class="code_param">x</a></span>.


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



