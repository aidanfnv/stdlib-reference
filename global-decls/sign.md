---
layout: stdlib-reference
---

# sign

## Description

Extract sign of value.



## Signature 

<pre>
<span class="code_keyword">int</span> <a href="sign">sign</a>&lt;<a href="sign#typeparam-T" class="code_type">T</a>&gt;(<a href="sign#typeparam-T" class="code_type">T</a> <a href="sign#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="sign#typeparam-T" class="code_type">T</a> : __BuiltinSignedArithmeticType;

<a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="sign#decl-N" class="code_var">N</a>&gt; <a href="sign">sign</a>&lt;<a href="sign#typeparam-T" class="code_type">T</a>, <a href="sign#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="sign#typeparam-T" class="code_type">T</a>, <a href="sign#decl-N" class="code_var">N</a>&gt; <a href="sign#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="sign#typeparam-T" class="code_type">T</a> : __BuiltinSignedArithmeticType;

<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<span class="code_keyword">int</span>, <a href="sign#decl-N" class="code_var">N</a>, <a href="sign#decl-M" class="code_var">M</a>&gt; <a href="sign">sign</a>&lt;<a href="sign#typeparam-T" class="code_type">T</a>, <a href="sign#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="sign#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="sign#typeparam-T" class="code_type">T</a>, <a href="sign#decl-N" class="code_var">N</a>, <a href="sign#decl-M" class="code_var">M</a>&gt; <a href="sign#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="sign#typeparam-T" class="code_type">T</a> : __BuiltinSignedArithmeticType;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: \_\_BuiltinSignedArithmeticType
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](sign#typeparam-T)
The value to extract the sign of.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
The value to extract the sign of.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index)\<[T](), [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>
The value to extract the sign of.


## Return value
-1 if <span class='code'><a href="sign#decl-x" class="code_param">x</a></span> is negative, 0 if <span class='code'><a href="sign#decl-x" class="code_param">x</a></span> is zero, and 1 if <span class='code'><a href="sign#decl-x" class="code_param">x</a></span> is positive.


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

#### wgsl
Available in all stages.

#### spirv
Available in all stages.



