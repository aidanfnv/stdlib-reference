---
layout: stdlib-reference
---

# asin

## Description

Arc sine. Returns the angle whose sine is the specified number.



## Signature 

<pre>
<a href="asin#typeparam-T" class="code_type">T</a> <a href="asin">asin</a>&lt;<a href="asin#typeparam-T" class="code_type">T</a>&gt;(<a href="asin#typeparam-T" class="code_type">T</a> <a href="asin#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="asin#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="asin#typeparam-T" class="code_type">T</a>, <a href="asin#decl-N" class="code_var">N</a>&gt; <a href="asin">asin</a>&lt;<a href="asin#typeparam-T" class="code_type">T</a>, <a href="asin#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="asin#typeparam-T" class="code_type">T</a>, <a href="asin#decl-N" class="code_var">N</a>&gt; <a href="asin#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="asin#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="asin#typeparam-T" class="code_type">T</a>, <a href="asin#decl-N" class="code_var">N</a>, <a href="asin#decl-M" class="code_var">M</a>&gt; <a href="asin">asin</a>&lt;<a href="asin#typeparam-T" class="code_type">T</a>, <a href="asin#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="asin#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="asin#typeparam-T" class="code_type">T</a>, <a href="asin#decl-N" class="code_var">N</a>, <a href="asin#decl-M" class="code_var">M</a>&gt; <a href="asin#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="asin#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](asin#typeparam-T)
The sine value.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The sine value.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index)\<[T](), [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>
The sine value.


## Return value
The angle in radians, in the range of [-pi/2, pi/2].


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



