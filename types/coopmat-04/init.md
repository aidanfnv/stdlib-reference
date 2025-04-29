---
layout: stdlib-reference
---

# CoopMat\<T, S:CoopMatScope, M:int, N:int, R:CoopMatMatrixUse\>\.init

## Description





## Signature 

<pre>
<a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="init">init</a>()
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="init">init</a>(
    <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> <a href="init#decl-t" class="code_param">t</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="init">init</a>&lt;<a href="init#typeparam-U" class="code_type">U</a>&gt;(
    <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="init#typeparam-U" class="code_type">U</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>, <a href="../types/coopmat-04/index#decl-M" class="code_var">M</a>, <a href="../types/coopmat-04/index#decl-N" class="code_var">N</a>, <a href="../types/coopmat-04/index#decl-R" class="code_var">R</a>&gt; <a href="init#decl-other" class="code_param">other</a>)
    <span class='code_keyword'>where</span> <a href="init#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="init">init</a>(
    <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>, <a href="../types/coopmat-04/index#decl-M" class="code_var">M</a>, <a href="../types/coopmat-04/index#decl-N" class="code_var">N</a>, <a href="../types/coopmat-04/index#decl-R" class="code_var">R</a>&gt; <a href="init#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="init">init</a>(
    <span class="code_keyword">int</span> <a href="init#decl-i" class="code_param">i</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index)

## Parameters

####  <a id="decl-t"></a>t  : [T](../types/coopmat-04/index#typeparam-T)
####  <a id="decl-other"></a>other  : [CoopMat](../types/coopmat-04/index)\<U, [S](../types/coopmat-04/index#decl-S), [M](../types/coopmat-04/index#decl-M), [N](../types/coopmat-04/index#decl-N), [R](../types/coopmat-04/index#decl-R)\>
####  <a id="decl-x"></a>x  : [CoopMat](../types/coopmat-04/index)\<[T](../types/coopmat-04/index#typeparam-T), [S](../types/coopmat-04/index#decl-S), [M](../types/coopmat-04/index#decl-M), [N](../types/coopmat-04/index#decl-N), [R](../types/coopmat-04/index#decl-R)\>
####  <a id="decl-i"></a>i  : int

## Availability and Requirements

Defined for the following targets:

#### spirv
Available in all stages.

Requires capability: `spvCooperativeMatrixKHR`.


