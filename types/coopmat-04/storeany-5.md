---
layout: stdlib-reference
---

# CoopMat\<T, S:CoopMatScope, M:int, N:int, R:CoopMatMatrixUse\>\.storeAny

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="storeany-5">storeAny</a>&lt;<a href="storeany-5#typeparam-U" class="code_type">U</a>, <a href="storeany-5#decl-V" class="code_var">V</a>:<span class="code_keyword">int</span>&gt;(
    <a href="storeany-5#typeparam-U" class="code_type">U</a>[<a href="storeany-5#decl-V" class="code_var">V</a>] <a href="storeany-5#decl-data" class="code_param">data</a>,
    <span class="code_keyword">uint</span> <a href="storeany-5#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="storeany-5#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index" class="code_type">CoopMatMatrixLayout</a> <a href="storeany-5#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<span class="code_keyword">void</span> <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="storeany-5">storeAny</a>&lt;<a href="storeany-5#typeparam-U" class="code_type">U</a>, <a href="storeany-5#decl-V" class="code_var">V</a>:<span class="code_keyword">int</span>, <a href="storeany-5#decl-L" class="code_var">L</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="storeany-5#typeparam-U" class="code_type">U</a>, <a href="storeany-5#decl-L" class="code_var">L</a>&gt;[V] <a href="storeany-5#decl-data" class="code_param">data</a>,
    <span class="code_keyword">uint</span> <a href="storeany-5#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="storeany-5#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index" class="code_type">CoopMatMatrixLayout</a> <a href="storeany-5#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U
####  <a id="decl-V"></a>V  : int
####  <a id="decl-L"></a>L  : int

## Parameters

####  <a id="decl-data"></a>data  : [U](storeany-5#typeparam-U) \[ [V](storeany-5#decl-V) \]
####  <a id="decl-element"></a>element  : uint
####  <a id="decl-stride"></a>stride  : uint
####  <a id="decl-matrixLayout"></a>matrixLayout  : [CoopMatMatrixLayout](../types/coopmatmatrixlayout-047d/index)
####  <a id="decl-data"></a>data  : [vector](../types/vector/index)\<U, L\> \[ V \]

## Availability and Requirements

Defined for the following targets:

#### spirv
Available in all stages.

Requires capability: `spvCooperativeMatrixKHR`.


