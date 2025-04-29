---
layout: stdlib-reference
---

# fmod

## Description

Floating point remainder of x/y.
The floating-point remainder is calculated such that x = i * y + f,
where i is an integer, f has the same sign as x, and the absolute value
of f is less than the absolute value of y.



## Signature 

<pre>
<a href="fmod#typeparam-T" class="code_type">T</a> <a href="fmod">fmod</a>&lt;<a href="fmod#typeparam-T" class="code_type">T</a>&gt;(
    <a href="fmod#typeparam-T" class="code_type">T</a> <a href="fmod#decl-x" class="code_param">x</a>,
    <a href="fmod#typeparam-T" class="code_type">T</a> <a href="fmod#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="fmod#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="fmod#typeparam-T" class="code_type">T</a>, <a href="fmod#decl-N" class="code_var">N</a>&gt; <a href="fmod">fmod</a>&lt;<a href="fmod#typeparam-T" class="code_type">T</a>, <a href="fmod#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="fmod#typeparam-T" class="code_type">T</a>, <a href="fmod#decl-N" class="code_var">N</a>&gt; <a href="fmod#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="fmod#typeparam-T" class="code_type">T</a>, <a href="fmod#decl-N" class="code_var">N</a>&gt; <a href="fmod#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="fmod#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="fmod#typeparam-T" class="code_type">T</a>, <a href="fmod#decl-N" class="code_var">N</a>, <a href="fmod#decl-M" class="code_var">M</a>&gt; <a href="fmod">fmod</a>&lt;<a href="fmod#typeparam-T" class="code_type">T</a>, <a href="fmod#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="fmod#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="fmod#typeparam-T" class="code_type">T</a>, <a href="fmod#decl-N" class="code_var">N</a>, <a href="fmod#decl-M" class="code_var">M</a>&gt; <a href="fmod#decl-x" class="code_param">x</a>,
    <a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="fmod#typeparam-T" class="code_type">T</a>, <a href="fmod#decl-N" class="code_var">N</a>, <a href="fmod#decl-M" class="code_var">M</a>&gt; <a href="fmod#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="fmod#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](fmod#typeparam-T)
The dividend.

####  <a id="decl-y"></a>y  : [T](fmod#typeparam-T)
The divisor.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The dividend.

####  <a id="decl-y"></a>y  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The divisor.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index)\<[T](), [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>
The dividend.

####  <a id="decl-y"></a>y  : [matrix](../types/matrix/index)\<[T](), [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>
The divisor.


## Return value
The floating-point remainder of x/y.


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



