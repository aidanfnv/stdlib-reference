---
layout: stdlib-reference
---

# frexp

## Description

Split float into mantissa and exponent.



## Signature 

<pre>
<a href="frexp#typeparam-T" class="code_type">T</a> <a href="frexp">frexp</a>&lt;<a href="frexp#typeparam-T" class="code_type">T</a>&gt;(
    <a href="frexp#typeparam-T" class="code_type">T</a> <a href="frexp#decl-x" class="code_param">x</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">int</span> <a href="frexp#decl-exp" class="code_param">exp</a>)
    <span class='code_keyword'>where</span> <a href="frexp#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="frexp#typeparam-T" class="code_type">T</a>, <a href="frexp#decl-N" class="code_var">N</a>&gt; <a href="frexp">frexp</a>&lt;<a href="frexp#typeparam-T" class="code_type">T</a>, <a href="frexp#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="frexp#typeparam-T" class="code_type">T</a>, <a href="frexp#decl-N" class="code_var">N</a>&gt; <a href="frexp#decl-x" class="code_param">x</a>,
    <span class="code_keyword">out</span> <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="frexp#decl-N" class="code_var">N</a>&gt; <a href="frexp#decl-exp" class="code_param">exp</a>)
    <span class='code_keyword'>where</span> <a href="frexp#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="frexp#typeparam-T" class="code_type">T</a>, <a href="frexp#decl-N" class="code_var">N</a>, <a href="frexp#decl-M" class="code_var">M</a>&gt; <a href="frexp">frexp</a>&lt;<a href="frexp#typeparam-T" class="code_type">T</a>, <a href="frexp#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="frexp#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="frexp#decl-L" class="code_var">L</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="frexp#typeparam-T" class="code_type">T</a>, <a href="frexp#decl-N" class="code_var">N</a>, <a href="frexp#decl-M" class="code_var">M</a>&gt; <a href="frexp#decl-x" class="code_param">x</a>,
    <span class="code_keyword">out</span> <a href="../types/matrix/index" class="code_type">matrix</a>&lt;<span class="code_keyword">int</span>, <a href="frexp#decl-N" class="code_var">N</a>, <a href="frexp#decl-M" class="code_var">M</a>&gt; <a href="frexp#decl-exp" class="code_param">exp</a>)
    <span class='code_keyword'>where</span> <a href="frexp#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int
####  <a id="decl-L"></a>L  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](frexp#typeparam-T)
The input value.

####  <a id="decl-exp"></a>exp  : int
\[out\] The output exponent.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The input value.

####  <a id="decl-exp"></a>exp  : [vector](../types/vector/index)\<int, [N](../types/vector/index#decl-N)\>
\[out\] The output exponent.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index)\<[T](), [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>
The input value.

####  <a id="decl-exp"></a>exp  : [matrix](../types/matrix/index)\<int, [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>
\[out\] The output exponent.


## Return value
The mantissa of <span class='code'><a href="frexp#decl-x" class="code_param">x</a></span>.


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



