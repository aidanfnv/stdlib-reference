---
layout: stdlib-reference
---

# fma

## Description

Fused multiply-add.



## Signature 

<pre>
/// Requires Capability Set 1:
<a href="fma#typeparam-T" class="code_type">T</a> <a href="fma">fma</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>&gt;(
    <a href="fma#typeparam-T" class="code_type">T</a> <a href="fma#decl-a" class="code_param">a</a>,
    <a href="fma#typeparam-T" class="code_type">T</a> <a href="fma#decl-b" class="code_param">b</a>,
    <a href="fma#typeparam-T" class="code_type">T</a> <a href="fma#decl-c" class="code_param">c</a>)
    <span class='code_keyword'>where</span> <a href="fma#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 1:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>&gt; <a href="fma">fma</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>&gt; <a href="fma#decl-a" class="code_param">a</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>&gt; <a href="fma#decl-b" class="code_param">b</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>&gt; <a href="fma#decl-c" class="code_param">c</a>)
    <span class='code_keyword'>where</span> <a href="fma#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 1:
<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>, <a href="fma#decl-M" class="code_var">M</a>&gt; <a href="fma">fma</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="fma#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>, <a href="fma#decl-M" class="code_var">M</a>&gt; <a href="fma#decl-a" class="code_param">a</a>,
    <a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>, <a href="fma#decl-M" class="code_var">M</a>&gt; <a href="fma#decl-b" class="code_param">b</a>,
    <a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>, <a href="fma#decl-M" class="code_var">M</a>&gt; <a href="fma#decl-c" class="code_param">c</a>)
    <span class='code_keyword'>where</span> <a href="fma#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 2:
<a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>&gt; <a href="fma">fma</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>&gt; <a href="fma#decl-a" class="code_param">a</a>,
    <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>&gt; <a href="fma#decl-b" class="code_param">b</a>,
    <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="fma#typeparam-T" class="code_type">T</a>, <a href="fma#decl-N" class="code_var">N</a>&gt; <a href="fma#decl-c" class="code_param">c</a>)
    <span class='code_keyword'>where</span> <a href="fma#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-a"></a>a  : [T](fma#typeparam-T)
The first value to multiply.

####  <a id="decl-b"></a>b  : [T](fma#typeparam-T)
The second value to multiply.

####  <a id="decl-c"></a>c  : [T](fma#typeparam-T)
The value to add to the product of <span class='code'><a href="fma#decl-a" class="code_param">a</a></span> and <span class='code'><a href="fma#decl-b" class="code_param">b</a></span>.

####  <a id="decl-a"></a>a  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The first value to multiply.

####  <a id="decl-b"></a>b  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The second value to multiply.

####  <a id="decl-c"></a>c  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The value to add to the product of <span class='code'><a href="fma#decl-a" class="code_param">a</a></span> and <span class='code'><a href="fma#decl-b" class="code_param">b</a></span>.

####  <a id="decl-a"></a>a  : [matrix](../types/matrix/index)\<[T](), [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>
The first value to multiply.

####  <a id="decl-b"></a>b  : [matrix](../types/matrix/index)\<[T](), [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>
The second value to multiply.

####  <a id="decl-c"></a>c  : [matrix](../types/matrix/index)\<[T](), [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>
The value to add to the product of <span class='code'><a href="fma#decl-a" class="code_param">a</a></span> and <span class='code'><a href="fma#decl-b" class="code_param">b</a></span>.

####  <a id="decl-a"></a>a  : [CoopVec](../types/coopvec-04/index)\<[T](../types/coopvec-04/index#typeparam-T), [N](../types/coopvec-04/index#decl-N)\>
The first value to multiply.

####  <a id="decl-b"></a>b  : [CoopVec](../types/coopvec-04/index)\<[T](../types/coopvec-04/index#typeparam-T), [N](../types/coopvec-04/index#decl-N)\>
The second value to multiply.

####  <a id="decl-c"></a>c  : [CoopVec](../types/coopvec-04/index)\<[T](../types/coopvec-04/index#typeparam-T), [N](../types/coopvec-04/index#decl-N)\>
The value to add to the product of <span class='code'><a href="fma#decl-a" class="code_param">a</a></span> and <span class='code'><a href="fma#decl-b" class="code_param">b</a></span>.


## Return value
The result of <span class='code'><a href="fma#decl-a" class="code_param">a</a>*<a href="fma#decl-b" class="code_param">b</a>+<a href="fma#decl-c" class="code_param">c</a></span>.


## Availability and Requirements

### Capability Set 1

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


### Capability Set 2

Defined for the following targets:

#### hlsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvCooperativeVectorNV`.


