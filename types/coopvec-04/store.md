---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.store

## Description

Store all elements of this CoopVec into a buffer at a specified offset.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="store">store</a>(
    <a href="../types/rwbyteaddressbuffer-0126d/index" class="code_type">RWByteAddressBuffer</a> <a href="store#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">int</span> <a href="store#decl-byteOffset16ByteAligned" class="code_param">byteOffset16ByteAligned</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<span class="code_keyword">void</span> <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="store">store</a>(
    <a href="../types/rwstructuredbuffer-012c/index" class="code_type">RWStructuredBuffer</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/defaultdatalayout-07b/index" class="code_type">DefaultDataLayout</a>&gt; <a href="store#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">int</span> <a href="store#decl-byteOffset16ByteAligned" class="code_param">byteOffset16ByteAligned</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<span class="code_keyword">void</span> <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="store">store</a>&lt;<a href="store#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>[M] <a href="store#decl-data" class="code_param">data</a>,
    <span class="code_keyword">int</span> <a href="store#decl-byteOffset16ByteAligned" class="code_param">byteOffset16ByteAligned</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-buffer"></a>buffer  : [RWByteAddressBuffer](../types/rwbyteaddressbuffer-0126d/index)
The destination buffer to store the values into.

####  <a id="decl-byteOffset16ByteAligned"></a>byteOffset16ByteAligned  : int = 0
The byte offset from the start of the buffer where the data will be stored. Must be 16-byte aligned.

####  <a id="decl-buffer"></a>buffer  : [RWStructuredBuffer](../types/rwstructuredbuffer-012c/index)\<[T](../types/rwstructuredbuffer-012c/index#typeparam-T), [DefaultDataLayout](../types/defaultdatalayout-07b/index)\>
The destination buffer to store the values into.

####  <a id="decl-data"></a>data  : [T](../types/coopvec-04/index#typeparam-T) \[ M \]

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


