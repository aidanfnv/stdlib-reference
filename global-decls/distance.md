---
layout: stdlib-reference
---

# distance

## Description

Vector distance. Returns the distance between two points.



## Signature 

<pre>
<a href="distance#typeparam-T" class="code_type">T</a> <a href="distance">distance</a>&lt;<a href="distance#typeparam-T" class="code_type">T</a>, <a href="distance#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="distance#typeparam-T" class="code_type">T</a>, <a href="distance#decl-N" class="code_var">N</a>&gt; <a href="distance#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="distance#typeparam-T" class="code_type">T</a>, <a href="distance#decl-N" class="code_var">N</a>&gt; <a href="distance#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="distance#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="distance#typeparam-T" class="code_type">T</a> <a href="distance">distance</a>&lt;<a href="distance#typeparam-T" class="code_type">T</a>&gt;(
    <a href="distance#typeparam-T" class="code_type">T</a> <a href="distance#decl-x" class="code_param">x</a>,
    <a href="distance#typeparam-T" class="code_type">T</a> <a href="distance#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="distance#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-x"></a>x  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The first point.

####  <a id="decl-y"></a>y  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The second point.

####  <a id="decl-x"></a>x  : [T](distance#typeparam-T)
The first point.

####  <a id="decl-y"></a>y  : [T](distance#typeparam-T)
The second point.


## Return value
The distance between <span class='code'><a href="distance#decl-x" class="code_param">x</a></span> and <span class='code'><a href="distance#decl-y" class="code_param">y</a></span>.

## Remarks
This function is equivalent to <span class='code'><a href="">length</a>(<a href="#decl-x" class="code_param">x</a>-y)</span>. When <span class='code'><a href="distance#decl-x" class="code_param">x</a></span> and <span class='code'><a href="distance#decl-y" class="code_param">y</a></span> are scalars, this function is equivalent to <span class='code'><a href="">abs</a>(<a href="#decl-x" class="code_param">x</a>-y)</span>.


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



