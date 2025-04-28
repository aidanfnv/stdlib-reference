---
layout: stdlib-reference
---

# CoopMat\<T, S:CoopMatScope, M:int, N:int, R:CoopMatMatrixUse\>\.copyFrom

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/coopmat-04/index.html" class="code_type">CoopMat</a>&lt;<a href="../types/coopmat-04/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/coopmat-04/index.html#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index.html" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index.html" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="copyfrom-4.html">copyFrom</a>&lt;<a href="copyfrom-4.html#typeparam-U" class="code_type">U</a>&gt;(
    <a href="../types/coopmat-04/index.html" class="code_type">CoopMat</a>&lt;<a href="copyfrom-4.html#typeparam-U" class="code_type">U</a>, <a href="../types/coopmat-04/index.html#decl-S" class="code_var">S</a>, <a href="../types/coopmat-04/index.html#decl-M" class="code_var">M</a>, <a href="../types/coopmat-04/index.html#decl-N" class="code_var">N</a>, <a href="../types/coopmat-04/index.html#decl-R" class="code_var">R</a>&gt; <a href="copyfrom-4.html#decl-other" class="code_param">other</a>)
    <span class='code_keyword'>where</span> <a href="copyfrom-4.html#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="../types/coopmat-04/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index.html)

## Parameters

####  <a id="decl-other"></a>other  : [CoopMat](../types/coopmat-04/index.html)\<U, [S](../types/coopmat-04/index.html#decl-S), [M](../types/coopmat-04/index.html#decl-M), [N](../types/coopmat-04/index.html#decl-N), [R](../types/coopmat-04/index.html#decl-R)\>

## Availability and Requirements

Defined for the following targets:

#### spirv
Available in all stages.

Requires capability: `spvCooperativeMatrixKHR`.


