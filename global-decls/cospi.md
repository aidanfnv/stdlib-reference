---
layout: stdlib-reference
---

# cospi

## Description

Compute the cosine of pi times the input.



## Signature 

<pre>
<a href="cospi#typeparam-T" class="code_type">T</a> <a href="cospi">cospi</a>&lt;<a href="cospi#typeparam-T" class="code_type">T</a>&gt;(<a href="cospi#typeparam-T" class="code_type">T</a> <a href="cospi#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="cospi#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="cospi#typeparam-T" class="code_type">T</a>, <a href="cospi#decl-N" class="code_var">N</a>&gt; <a href="cospi">cospi</a>&lt;<a href="cospi#typeparam-T" class="code_type">T</a>, <a href="cospi#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="cospi#typeparam-T" class="code_type">T</a>, <a href="cospi#decl-N" class="code_var">N</a>&gt; <a href="cospi#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="cospi#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](cospi#typeparam-T)
The input value.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The input value.


## Return value
The cosine of pi times the input.

## Remarks
This function is equivalent to <span class='code'><a href="">cos</a>(PI*<a href="#decl-x" class="code_param">x</a>)</span>. On Metal, this function is implemented using the <span class='code'><a href="cospi">cospi</a></span> intrinsic.


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



