---
layout: stdlib-reference
---

# round

## Description

Round-to-nearest.



## Signature 

<pre>
<a href="round#typeparam-T" class="code_type">T</a> <a href="round">round</a>&lt;<a href="round#typeparam-T" class="code_type">T</a>&gt;(<a href="round#typeparam-T" class="code_type">T</a> <a href="round#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="round#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="round#typeparam-T" class="code_type">T</a>, <a href="round#decl-N" class="code_var">N</a>&gt; <a href="round">round</a>&lt;<a href="round#typeparam-T" class="code_type">T</a>, <a href="round#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="round#typeparam-T" class="code_type">T</a>, <a href="round#decl-N" class="code_var">N</a>&gt; <a href="round#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="round#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="round#typeparam-T" class="code_type">T</a>, <a href="round#decl-N" class="code_var">N</a>, <a href="round#decl-M" class="code_var">M</a>&gt; <a href="round">round</a>&lt;<a href="round#typeparam-T" class="code_type">T</a>, <a href="round#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="round#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="round#typeparam-T" class="code_type">T</a>, <a href="round#decl-N" class="code_var">N</a>, <a href="round#decl-M" class="code_var">M</a>&gt; <a href="round#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="round#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](round#typeparam-T)
The value to round.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The value to round.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index)\<[T](), [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>
The value to round.


## Return value
The value rounded to the nearest integer.

## Remarks
Rounding behavior of .5 is determined by target intrinsic.


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



