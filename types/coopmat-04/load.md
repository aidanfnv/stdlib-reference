---
layout: stdlib-reference
---

# CoopMat\<T, S:CoopMatScope, M:int, N:int, R:CoopMatMatrixUse\>\.load

## Description





## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>, <a href="../types/coopmat-04/index#decl-M" class="code_var">M</a>, <a href="../types/coopmat-04/index#decl-N" class="code_var">N</a>, <a href="../types/coopmat-04/index#decl-R" class="code_var">R</a>&gt; <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="load">load</a>(
    <a href="../types/byteaddressbuffer-04b/index" class="code_type">ByteAddressBuffer</a> <a href="load#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index" class="code_type">CoopMatMatrixLayout</a> <a href="load#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<span class='code_keyword'>static</span> <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>, <a href="../types/coopmat-04/index#decl-M" class="code_var">M</a>, <a href="../types/coopmat-04/index#decl-N" class="code_var">N</a>, <a href="../types/coopmat-04/index#decl-R" class="code_var">R</a>&gt; <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="load">load</a>(
    <a href="../types/rwbyteaddressbuffer-0126d/index" class="code_type">RWByteAddressBuffer</a> <a href="load#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index" class="code_type">CoopMatMatrixLayout</a> <a href="load#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<span class='code_keyword'>static</span> <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>, <a href="../types/coopmat-04/index#decl-M" class="code_var">M</a>, <a href="../types/coopmat-04/index#decl-N" class="code_var">N</a>, <a href="../types/coopmat-04/index#decl-R" class="code_var">R</a>&gt; <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="load">load</a>(
    <a href="../types/structuredbuffer-0a/index" class="code_type">StructuredBuffer</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/defaultdatalayout-07b/index" class="code_type">DefaultDataLayout</a>&gt; <a href="load#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index" class="code_type">CoopMatMatrixLayout</a> <a href="load#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<span class='code_keyword'>static</span> <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>, <a href="../types/coopmat-04/index#decl-M" class="code_var">M</a>, <a href="../types/coopmat-04/index#decl-N" class="code_var">N</a>, <a href="../types/coopmat-04/index#decl-R" class="code_var">R</a>&gt; <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="load">load</a>(
    <a href="../types/rwstructuredbuffer-012c/index" class="code_type">RWStructuredBuffer</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/defaultdatalayout-07b/index" class="code_type">DefaultDataLayout</a>&gt; <a href="load#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index" class="code_type">CoopMatMatrixLayout</a> <a href="load#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<span class='code_keyword'>static</span> <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>, <a href="../types/coopmat-04/index#decl-M" class="code_var">M</a>, <a href="../types/coopmat-04/index#decl-N" class="code_var">N</a>, <a href="../types/coopmat-04/index#decl-R" class="code_var">R</a>&gt; <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="load">load</a>(
    <a href="../types/ptr-0/index" class="code_type">Ptr</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>&gt; <a href="load#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index" class="code_type">CoopMatMatrixLayout</a> <a href="load#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<span class='code_keyword'>static</span> <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>, <a href="../types/coopmat-04/index#decl-M" class="code_var">M</a>, <a href="../types/coopmat-04/index#decl-N" class="code_var">N</a>, <a href="../types/coopmat-04/index#decl-R" class="code_var">R</a>&gt; <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="load">load</a>&lt;<a href="load#decl-U" class="code_var">U</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>[U] <a href="load#decl-data" class="code_param">data</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index" class="code_type">CoopMatMatrixLayout</a> <a href="load#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="decl-U"></a>U  : int

## Parameters

####  <a id="decl-buffer"></a>buffer  : [ByteAddressBuffer](../types/byteaddressbuffer-04b/index)
####  <a id="decl-element"></a>element  : uint
####  <a id="decl-stride"></a>stride  : uint
####  <a id="decl-matrixLayout"></a>matrixLayout  : [CoopMatMatrixLayout](../types/coopmatmatrixlayout-047d/index)
####  <a id="decl-buffer"></a>buffer  : [RWByteAddressBuffer](../types/rwbyteaddressbuffer-0126d/index)
####  <a id="decl-buffer"></a>buffer  : [StructuredBuffer](../types/structuredbuffer-0a/index)\<[T](../types/structuredbuffer-0a/index#typeparam-T), [DefaultDataLayout](../types/defaultdatalayout-07b/index)\>
####  <a id="decl-buffer"></a>buffer  : [RWStructuredBuffer](../types/rwstructuredbuffer-012c/index)\<[T](../types/rwstructuredbuffer-012c/index#typeparam-T), [DefaultDataLayout](../types/defaultdatalayout-07b/index)\>
####  <a id="decl-buffer"></a>buffer  : [Ptr](../types/ptr-0/index)\<[T](../types/ptr-0/index#typeparam-T)\>
####  <a id="decl-data"></a>data  : [T](../types/coopmat-04/index#typeparam-T) \[ U \]

## Availability and Requirements

Defined for the following targets:

#### spirv
Available in all stages.

Requires capability: `spvCooperativeMatrixKHR`.


