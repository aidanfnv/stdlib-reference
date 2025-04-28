---
layout: stdlib-reference
---

# coopVecLoadGroupshared

## Description





## Signature 

<pre>
<a href="../../types/coopvec-04/index.html" class="code_type">CoopVec</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html">coopVecLoadGroupshared</a>&lt;<a href=".html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <span class="code_keyword">const</span> <a href=".html#typeparam-T" class="code_type">T</a>[<a href=".html#decl-M" class="code_var">M</a>] <a href=".html#decl-data" class="code_param">data</a>,
    <span class="code_keyword">int</span> <a href=".html#decl-byteOffset16ByteAligned" class="code_param">byteOffset16ByteAligned</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int
####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../../interfaces/0_builtinarithmetictype-029j/index.html)
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-data"></a>data  : [T](.html#typeparam-T) \[ [M](.html#decl-M) \]
####  <a id="decl-byteOffset16ByteAligned"></a>byteOffset16ByteAligned  : int = 0

## Availability and Requirements

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


