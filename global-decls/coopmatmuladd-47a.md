---
layout: stdlib-reference
---

# coopMatMulAdd

## Description





## Signature 

<pre>
<a href="../../types/coopmat-04/index.html" class="code_type">CoopMat</a>&lt;<a href=".html#typeparam-V" class="code_type">V</a>, <a href=".html#decl-S" class="code_var">S</a>, <a href=".html#decl-M" class="code_var">M</a>, <a href=".html#decl-N" class="code_var">N</a>, <a href=".html#decl-RC" class="code_var">RC</a>&gt; <a href=".html">coopMatMulAdd</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#typeparam-U" class="code_type">U</a>, <a href=".html#typeparam-V" class="code_type">V</a>, <a href=".html#decl-S" class="code_var">S</a>:<a href="../../types/coopmatscope-047/index.html" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, K:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, RA:<a href="../../types/coopmatmatrixuse-047d/index.html" class="code_type">CoopMatMatrixUse</a>, RB:<a href="../../types/coopmatmatrixuse-047d/index.html" class="code_type">CoopMatMatrixUse</a>, RC:<a href="../../types/coopmatmatrixuse-047d/index.html" class="code_type">CoopMatMatrixUse</a>&gt;(
    <a href="../../types/coopmat-04/index.html" class="code_type">CoopMat</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-S" class="code_var">S</a>, <a href=".html#decl-M" class="code_var">M</a>, <a href=".html#decl-K" class="code_var">K</a>, <a href=".html#decl-RA" class="code_var">RA</a>&gt; <a href=".html#decl-matA" class="code_param">matA</a>,
    <a href="../../types/coopmat-04/index.html" class="code_type">CoopMat</a>&lt;<a href=".html#typeparam-U" class="code_type">U</a>, <a href=".html#decl-S" class="code_var">S</a>, <a href=".html#decl-K" class="code_var">K</a>, <a href=".html#decl-N" class="code_var">N</a>, <a href=".html#decl-RB" class="code_var">RB</a>&gt; <a href=".html#decl-matB" class="code_param">matB</a>,
    <a href="../../types/coopmat-04/index.html" class="code_type">CoopMat</a>&lt;<a href=".html#typeparam-V" class="code_type">V</a>, <a href=".html#decl-S" class="code_var">S</a>, <a href=".html#decl-M" class="code_var">M</a>, <a href=".html#decl-N" class="code_var">N</a>, <a href=".html#decl-RC" class="code_var">RC</a>&gt; <a href=".html#decl-matC" class="code_param">matC</a>,
    <a href="../../types/coopmatmatrixoperands-047d/index.html" class="code_type">CoopMatMatrixOperands</a> <a href=".html#decl-operands" class="code_param">operands</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href=".html#typeparam-U" class="code_type">U</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href=".html#typeparam-V" class="code_type">V</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../../interfaces/0_builtinarithmetictype-029j/index.html)
####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../../interfaces/0_builtinarithmetictype-029j/index.html)
####  <a id="typeparam-V"></a>V: [\_\_BuiltinArithmeticType](../../interfaces/0_builtinarithmetictype-029j/index.html)
####  <a id="decl-S"></a>S  : [CoopMatScope](../../types/coopmatscope-047/index.html)
####  <a id="decl-M"></a>M  : int
####  <a id="decl-K"></a>K  : int
####  <a id="decl-N"></a>N  : int
####  <a id="decl-RA"></a>RA  : [CoopMatMatrixUse](../../types/coopmatmatrixuse-047d/index.html)
####  <a id="decl-RB"></a>RB  : [CoopMatMatrixUse](../../types/coopmatmatrixuse-047d/index.html)
####  <a id="decl-RC"></a>RC  : [CoopMatMatrixUse](../../types/coopmatmatrixuse-047d/index.html)

## Parameters

####  <a id="decl-matA"></a>matA  : [CoopMat](../../types/coopmat-04/index.html)\<[T](../../types/coopmat-04/index.html#typeparam-T), [S](../../types/coopmat-04/index.html#decl-S), [M](../../types/coopmat-04/index.html#decl-M), K, RA\>
####  <a id="decl-matB"></a>matB  : [CoopMat](../../types/coopmat-04/index.html)\<U, [S](../../types/coopmat-04/index.html#decl-S), K, [N](../../types/coopmat-04/index.html#decl-N), RB\>
####  <a id="decl-matC"></a>matC  : [CoopMat](../../types/coopmat-04/index.html)\<V, [S](../../types/coopmat-04/index.html#decl-S), [M](../../types/coopmat-04/index.html#decl-M), [N](../../types/coopmat-04/index.html#decl-N), RC\>
####  <a id="decl-operands"></a>operands  : [CoopMatMatrixOperands](../../types/coopmatmatrixoperands-047d/index.html)

## Availability and Requirements

Defined for the following targets:

#### spirv
Available in all stages.

Requires capability: `spvCooperativeMatrixKHR`.


