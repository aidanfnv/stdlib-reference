---
layout: stdlib-reference
---

# dot

## Description

Vector dot product. Returns the dot product of two vectors.



## Signature 

<pre>
<a href="dot#typeparam-T" class="code_type">T</a> <a href="dot">dot</a>&lt;<a href="dot#typeparam-T" class="code_type">T</a>&gt;(
    <a href="dot#typeparam-T" class="code_type">T</a> <a href="dot#decl-x" class="code_param">x</a>,
    <a href="dot#typeparam-T" class="code_type">T</a> <a href="dot#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="dot#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="dot#typeparam-T" class="code_type">T</a> <a href="dot">dot</a>&lt;<a href="dot#typeparam-T" class="code_type">T</a>, <a href="dot#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="dot#typeparam-T" class="code_type">T</a>, <a href="dot#decl-N" class="code_var">N</a>&gt; <a href="dot#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="dot#typeparam-T" class="code_type">T</a>, <a href="dot#decl-N" class="code_var">N</a>&gt; <a href="dot#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="dot#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="dot#typeparam-T" class="code_type">T</a> <a href="dot">dot</a>&lt;<a href="dot#typeparam-T" class="code_type">T</a>, <a href="dot#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="dot#typeparam-T" class="code_type">T</a>, <a href="dot#decl-N" class="code_var">N</a>&gt; <a href="dot#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="dot#typeparam-T" class="code_type">T</a>, <a href="dot#decl-N" class="code_var">N</a>&gt; <a href="dot#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="dot#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index" class="code_type">__BuiltinIntegerType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index)
####  <a id="decl-N"></a>N  : int
####  <a id="typeparam-T"></a>T: [\_\_BuiltinIntegerType](../interfaces/0_builtinintegertype-029g/index)

## Parameters

####  <a id="decl-x"></a>x  : [T](dot#typeparam-T)
The first vector.

####  <a id="decl-y"></a>y  : [T](dot#typeparam-T)
The second vector.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The first vector.

####  <a id="decl-y"></a>y  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The second vector.


## Return value
The dot product of <span class='code'><a href="dot#decl-x" class="code_param">x</a></span> and <span class='code'><a href="dot#decl-y" class="code_param">y</a></span>.

## Remarks
When <span class='code'><a href="dot#decl-x" class="code_param">x</a></span> and <span class='code'><a href="dot#decl-y" class="code_param">y</a></span> are scalars, this function is equivalent to <span class='code'><a href="dot#decl-x" class="code_param">x</a>*<a href="dot#decl-y" class="code_param">y</a></span>.


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



