---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.storeAny

## Description

Store the value to a groupshared array of any type. This method is only available when targeting SPIR-V.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="storeany-5">storeAny</a>&lt;<a href="storeany-5#typeparam-U" class="code_type">U</a>, <a href="storeany-5#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="storeany-5#typeparam-U" class="code_type">U</a>[<a href="storeany-5#decl-M" class="code_var">M</a>] <a href="storeany-5#decl-data" class="code_param">data</a>,
    <span class="code_keyword">int</span> <a href="storeany-5#decl-byteOffset16ByteAligned" class="code_param">byteOffset16ByteAligned</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<span class="code_keyword">void</span> <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="storeany-5">storeAny</a>&lt;<a href="storeany-5#typeparam-U" class="code_type">U</a>, <a href="storeany-5#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="storeany-5#decl-L" class="code_var">L</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="storeany-5#typeparam-U" class="code_type">U</a>, <a href="storeany-5#decl-L" class="code_var">L</a>&gt;[M] <a href="storeany-5#decl-data" class="code_param">data</a>,
    <span class="code_keyword">int</span> <a href="storeany-5#decl-byteOffset16ByteAligned" class="code_param">byteOffset16ByteAligned</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U
####  <a id="decl-M"></a>M  : int
####  <a id="decl-L"></a>L  : int

## Parameters

####  <a id="decl-data"></a>data  : [U](storeany-5#typeparam-U) \[ [M](storeany-5#decl-M) \]
The destination array where the data will be stored. The array element type can be different from the CoopVec element type.

####  <a id="decl-byteOffset16ByteAligned"></a>byteOffset16ByteAligned  : int = 0
The byte offset from the start of <span class='code'><a href="storeany-5#decl-data" class="code_param">data</a></span>. Must be a multiple of 16 bytes.

####  <a id="decl-data"></a>data  : [vector](../types/vector/index)\<U, L\> \[ M \]
The destination array where the data will be stored. The array element type can be different from the CoopVec element type.


## Availability and Requirements

Defined for the following targets:

#### spirv
Available in all stages.

Requires capability: `spvCooperativeVectorNV`.


