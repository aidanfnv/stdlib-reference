---
layout: stdlib-reference
---

# coopVecMatMulAdd

## Description

Multiply a cooperative vector with a matrix and add a bias vector.



## Signature 

<pre>
/// Requires Capability Set 1:
<a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmuladd-47ad#decl-M" class="code_var">M</a>&gt; <a href="coopvecmatmuladd-47ad">coopVecMatMulAdd</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmuladd-47ad#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmuladd-47ad#decl-K" class="code_var">K</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmuladd-47ad#typeparam-U" class="code_type">U</a>&gt;(
    <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmuladd-47ad#decl-K" class="code_var">K</a>&gt; <a href="coopvecmatmuladd-47ad#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmuladd-47ad#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <a href="../types/rwbyteaddressbuffer-0126d/index" class="code_type">RWByteAddressBuffer</a> <a href="coopvecmatmuladd-47ad#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmuladd-47ad#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmuladd-47ad#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/rwbyteaddressbuffer-0126d/index" class="code_type">RWByteAddressBuffer</a> <a href="coopvecmatmuladd-47ad#decl-bias" class="code_param">bias</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmuladd-47ad#decl-biasOffset" class="code_param">biasOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmuladd-47ad#decl-biasInterpretation" class="code_param">biasInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index" class="code_type">CoopVecMatrixLayout</a> <a href="coopvecmatmuladd-47ad#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="coopvecmatmuladd-47ad#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="coopvecmatmuladd-47ad#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="coopvecmatmuladd-47ad#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopvecmatmuladd-47ad#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 1:
<a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmuladd-47ad#decl-M" class="code_var">M</a>&gt; <a href="coopvecmatmuladd-47ad">coopVecMatMulAdd</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmuladd-47ad#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmuladd-47ad#decl-K" class="code_var">K</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmuladd-47ad#typeparam-U" class="code_type">U</a>&gt;(
    <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmuladd-47ad#decl-K" class="code_var">K</a>&gt; <a href="coopvecmatmuladd-47ad#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmuladd-47ad#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <a href="../types/byteaddressbuffer-04b/index" class="code_type">ByteAddressBuffer</a> <a href="coopvecmatmuladd-47ad#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmuladd-47ad#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmuladd-47ad#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/byteaddressbuffer-04b/index" class="code_type">ByteAddressBuffer</a> <a href="coopvecmatmuladd-47ad#decl-bias" class="code_param">bias</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmuladd-47ad#decl-biasOffset" class="code_param">biasOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmuladd-47ad#decl-biasInterpretation" class="code_param">biasInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index" class="code_type">CoopVecMatrixLayout</a> <a href="coopvecmatmuladd-47ad#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="coopvecmatmuladd-47ad#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="coopvecmatmuladd-47ad#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="coopvecmatmuladd-47ad#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopvecmatmuladd-47ad#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 2:
<a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmuladd-47ad#decl-M" class="code_var">M</a>&gt; <a href="coopvecmatmuladd-47ad">coopVecMatMulAdd</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmuladd-47ad#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmuladd-47ad#decl-K" class="code_var">K</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmuladd-47ad#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmuladd-47ad#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>&gt;(
    <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmuladd-47ad#decl-K" class="code_var">K</a>&gt; <a href="coopvecmatmuladd-47ad#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmuladd-47ad#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <a href="../types/rwstructuredbuffer-012c/index" class="code_type">RWStructuredBuffer</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>, <a href="../types/defaultdatalayout-07b/index" class="code_type">DefaultDataLayout</a>&gt; <a href="coopvecmatmuladd-47ad#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmuladd-47ad#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmuladd-47ad#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/rwstructuredbuffer-012c/index" class="code_type">RWStructuredBuffer</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>, <a href="../types/defaultdatalayout-07b/index" class="code_type">DefaultDataLayout</a>&gt; <a href="coopvecmatmuladd-47ad#decl-bias" class="code_param">bias</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmuladd-47ad#decl-biasOffset" class="code_param">biasOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmuladd-47ad#decl-biasInterpretation" class="code_param">biasInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index" class="code_type">CoopVecMatrixLayout</a> <a href="coopvecmatmuladd-47ad#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="coopvecmatmuladd-47ad#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="coopvecmatmuladd-47ad#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="coopvecmatmuladd-47ad#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopvecmatmuladd-47ad#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 2:
<a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmuladd-47ad#decl-M" class="code_var">M</a>&gt; <a href="coopvecmatmuladd-47ad">coopVecMatMulAdd</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmuladd-47ad#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmuladd-47ad#decl-K" class="code_var">K</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmuladd-47ad#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmuladd-47ad#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>&gt;(
    <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmuladd-47ad#decl-K" class="code_var">K</a>&gt; <a href="coopvecmatmuladd-47ad#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmuladd-47ad#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <a href="../types/structuredbuffer-0a/index" class="code_type">StructuredBuffer</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>, <a href="../types/defaultdatalayout-07b/index" class="code_type">DefaultDataLayout</a>&gt; <a href="coopvecmatmuladd-47ad#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmuladd-47ad#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmuladd-47ad#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/structuredbuffer-0a/index" class="code_type">StructuredBuffer</a>&lt;<a href="coopvecmatmuladd-47ad#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>, <a href="../types/defaultdatalayout-07b/index" class="code_type">DefaultDataLayout</a>&gt; <a href="coopvecmatmuladd-47ad#decl-bias" class="code_param">bias</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmuladd-47ad#decl-biasOffset" class="code_param">biasOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmuladd-47ad#decl-biasInterpretation" class="code_param">biasInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index" class="code_type">CoopVecMatrixLayout</a> <a href="coopvecmatmuladd-47ad#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="coopvecmatmuladd-47ad#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="coopvecmatmuladd-47ad#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="coopvecmatmuladd-47ad#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopvecmatmuladd-47ad#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index)
####  <a id="decl-M"></a>M  : int
####  <a id="decl-K"></a>K  : int
####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index)
####  <a id="typeparam-IgnoredBufferElementType"></a>IgnoredBufferElementType

## Parameters

####  <a id="decl-input"></a>input  : [CoopVec](../types/coopvec-04/index)\<U, K\>
The input cooperative vector to multiply with the matrix.

####  <a id="decl-inputInterpretation"></a>inputInterpretation  : [CoopVecComponentType](../types/coopveccomponenttype-047g/index)
Specifies how to interpret the values in the input vector.

####  <a id="decl-matrix"></a>matrix  : [RWByteAddressBuffer](../types/rwbyteaddressbuffer-0126d/index)
The matrix buffer to multiply with.

####  <a id="decl-matrixOffset"></a>matrixOffset  : int
Byte offset into the matrix buffer.

####  <a id="decl-matrixInterpretation"></a>matrixInterpretation  : [CoopVecComponentType](../types/coopveccomponenttype-047g/index)
Specifies how to interpret the values in the matrix.

####  <a id="decl-bias"></a>bias  : [RWByteAddressBuffer](../types/rwbyteaddressbuffer-0126d/index)
The bias buffer to add after multiplication.

####  <a id="decl-biasOffset"></a>biasOffset  : int
Byte offset into the bias buffer.

####  <a id="decl-biasInterpretation"></a>biasInterpretation  : [CoopVecComponentType](../types/coopveccomponenttype-047g/index)
Specifies how to interpret the values in the bias vector.

####  <a id="decl-memoryLayout"></a>memoryLayout  : [CoopVecMatrixLayout](../types/coopvecmatrixlayout-047d/index)
Specifies the memory layout of the matrix (row-major or column-major).

####  <a id="decl-transpose"></a>transpose  : bool
Whether to transpose the matrix before multiplication.

####  <a id="decl-matrixStride"></a>matrixStride  : uint
The stride between matrix rows/columns in bytes.

####  <a id="decl-matrix"></a>matrix  : [ByteAddressBuffer](../types/byteaddressbuffer-04b/index)
The matrix buffer to multiply with.

####  <a id="decl-bias"></a>bias  : [ByteAddressBuffer](../types/byteaddressbuffer-04b/index)
The bias buffer to add after multiplication.

####  <a id="decl-matrix"></a>matrix  : [RWStructuredBuffer](../types/rwstructuredbuffer-012c/index)\<IgnoredBufferElementType, [DefaultDataLayout](../types/defaultdatalayout-07b/index)\>
The matrix buffer to multiply with.

####  <a id="decl-bias"></a>bias  : [RWStructuredBuffer](../types/rwstructuredbuffer-012c/index)\<IgnoredBufferElementType, [DefaultDataLayout](../types/defaultdatalayout-07b/index)\>
The bias buffer to add after multiplication.

####  <a id="decl-matrix"></a>matrix  : [StructuredBuffer](../types/structuredbuffer-0a/index)\<IgnoredBufferElementType, [DefaultDataLayout](../types/defaultdatalayout-07b/index)\>
The matrix buffer to multiply with.

####  <a id="decl-bias"></a>bias  : [StructuredBuffer](../types/structuredbuffer-0a/index)\<IgnoredBufferElementType, [DefaultDataLayout](../types/defaultdatalayout-07b/index)\>
The bias buffer to add after multiplication.


## Return value
A new cooperative vector containing the result of the matrix multiplication plus bias.


## Availability and Requirements

### Capability Set 1

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

### Capability Set 2

Defined for the following targets:

#### spirv
Available in all stages.

Requires capability: `spvCooperativeVectorNV`.


