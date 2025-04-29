---
layout: stdlib-reference
---

# coopMatMulAdd

## Description





## Signature 

<pre>
<a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="coopmatmuladd-47a#typeparam-V" class="code_type">V</a>, <a href="coopmatmuladd-47a#decl-S" class="code_var">S</a>, <a href="coopmatmuladd-47a#decl-M" class="code_var">M</a>, <a href="coopmatmuladd-47a#decl-N" class="code_var">N</a>, <a href="coopmatmuladd-47a#decl-RC" class="code_var">RC</a>&gt; <a href="coopmatmuladd-47a">coopMatMulAdd</a>&lt;<a href="coopmatmuladd-47a#typeparam-T" class="code_type">T</a>, <a href="coopmatmuladd-47a#typeparam-U" class="code_type">U</a>, <a href="coopmatmuladd-47a#typeparam-V" class="code_type">V</a>, <a href="coopmatmuladd-47a#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, K:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, RA:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>, RB:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>, RC:<a href="../types/coopmatmatrixuse-047d/index" class="code_type">CoopMatMatrixUse</a>&gt;(
    <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="coopmatmuladd-47a#typeparam-T" class="code_type">T</a>, <a href="coopmatmuladd-47a#decl-S" class="code_var">S</a>, <a href="coopmatmuladd-47a#decl-M" class="code_var">M</a>, <a href="coopmatmuladd-47a#decl-K" class="code_var">K</a>, <a href="coopmatmuladd-47a#decl-RA" class="code_var">RA</a>&gt; <a href="coopmatmuladd-47a#decl-matA" class="code_param">matA</a>,
    <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="coopmatmuladd-47a#typeparam-U" class="code_type">U</a>, <a href="coopmatmuladd-47a#decl-S" class="code_var">S</a>, <a href="coopmatmuladd-47a#decl-K" class="code_var">K</a>, <a href="coopmatmuladd-47a#decl-N" class="code_var">N</a>, <a href="coopmatmuladd-47a#decl-RB" class="code_var">RB</a>&gt; <a href="coopmatmuladd-47a#decl-matB" class="code_param">matB</a>,
    <a href="../types/coopmat-04/index" class="code_type">CoopMat</a>&lt;<a href="coopmatmuladd-47a#typeparam-V" class="code_type">V</a>, <a href="coopmatmuladd-47a#decl-S" class="code_var">S</a>, <a href="coopmatmuladd-47a#decl-M" class="code_var">M</a>, <a href="coopmatmuladd-47a#decl-N" class="code_var">N</a>, <a href="coopmatmuladd-47a#decl-RC" class="code_var">RC</a>&gt; <a href="coopmatmuladd-47a#decl-matC" class="code_param">matC</a>,
    <a href="../types/coopmatmatrixoperands-047d/index" class="code_type">CoopMatMatrixOperands</a> <a href="coopmatmuladd-47a#decl-operands" class="code_param">operands</a>)
    <span class='code_keyword'>where</span> <a href="coopmatmuladd-47a#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopmatmuladd-47a#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopmatmuladd-47a#typeparam-V" class="code_type">V</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index)
####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index)
####  <a id="typeparam-V"></a>V: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index)
####  <a id="decl-S"></a>S  : [CoopMatScope](../types/coopmatscope-047/index)
####  <a id="decl-M"></a>M  : int
####  <a id="decl-K"></a>K  : int
####  <a id="decl-N"></a>N  : int
####  <a id="decl-RA"></a>RA  : [CoopMatMatrixUse](../types/coopmatmatrixuse-047d/index)
####  <a id="decl-RB"></a>RB  : [CoopMatMatrixUse](../types/coopmatmatrixuse-047d/index)
####  <a id="decl-RC"></a>RC  : [CoopMatMatrixUse](../types/coopmatmatrixuse-047d/index)

## Parameters

####  <a id="decl-matA"></a>matA  : [CoopMat](../types/coopmat-04/index)\<[T](../types/coopmat-04/index#typeparam-T), [S](../types/coopmat-04/index#decl-S), [M](../types/coopmat-04/index#decl-M), K, RA\>
####  <a id="decl-matB"></a>matB  : [CoopMat](../types/coopmat-04/index)\<U, [S](../types/coopmat-04/index#decl-S), K, [N](../types/coopmat-04/index#decl-N), RB\>
####  <a id="decl-matC"></a>matC  : [CoopMat](../types/coopmat-04/index)\<V, [S](../types/coopmat-04/index#decl-S), [M](../types/coopmat-04/index#decl-M), [N](../types/coopmat-04/index#decl-N), RC\>
####  <a id="decl-operands"></a>operands  : [CoopMatMatrixOperands](../types/coopmatmatrixoperands-047d/index)

## Availability and Requirements

Defined for the following targets:

#### spirv
Available in all stages.

Requires capability: `spvCooperativeMatrixKHR`.


