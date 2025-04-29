---
layout: stdlib-reference
---

# coopVecMatMulPacked

## Description

Multiply a cooperative vector with a matrix and return the result.



## Signature 

<pre>
/// Requires Capability Set 1:
<a href="index.html" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmulpacked-47ad.html#decl-M" class="code_var">M</a>&gt; <a href="coopvecmatmulpacked-47ad.html">coopVecMatMulPacked</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmulpacked-47ad.html#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmulpacked-47ad.html#decl-PackedK" class="code_var">PackedK</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmulpacked-47ad.html#typeparam-U" class="code_type">U</a>&gt;(
    <a href="index.html" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmulpacked-47ad.html#decl-PackedK" class="code_var">PackedK</a>&gt; <a href="coopvecmatmulpacked-47ad.html#decl-input" class="code_param">input</a>,
    <a href="index.html" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmulpacked-47ad.html#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmulpacked-47ad.html#decl-k" class="code_param">k</a>,
    <a href="index.html" class="code_type">RWByteAddressBuffer</a> <a href="coopvecmatmulpacked-47ad.html#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmulpacked-47ad.html#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="index.html" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmulpacked-47ad.html#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="index.html" class="code_type">CoopVecMatrixLayout</a> <a href="coopvecmatmulpacked-47ad.html#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="coopvecmatmulpacked-47ad.html#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="coopvecmatmulpacked-47ad.html#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="coopvecmatmulpacked-47ad.html#typeparam-T" class="code_type">T</a> : <a href="index.html" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopvecmatmulpacked-47ad.html#typeparam-U" class="code_type">U</a> : <a href="index.html" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 1:
<a href="index.html" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmulpacked-47ad.html#decl-M" class="code_var">M</a>&gt; <a href="coopvecmatmulpacked-47ad.html">coopVecMatMulPacked</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmulpacked-47ad.html#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmulpacked-47ad.html#decl-PackedK" class="code_var">PackedK</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmulpacked-47ad.html#typeparam-U" class="code_type">U</a>&gt;(
    <a href="index.html" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmulpacked-47ad.html#decl-PackedK" class="code_var">PackedK</a>&gt; <a href="coopvecmatmulpacked-47ad.html#decl-input" class="code_param">input</a>,
    <a href="index.html" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmulpacked-47ad.html#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmulpacked-47ad.html#decl-k" class="code_param">k</a>,
    <a href="index.html" class="code_type">ByteAddressBuffer</a> <a href="coopvecmatmulpacked-47ad.html#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmulpacked-47ad.html#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="index.html" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmulpacked-47ad.html#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="index.html" class="code_type">CoopVecMatrixLayout</a> <a href="coopvecmatmulpacked-47ad.html#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="coopvecmatmulpacked-47ad.html#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="coopvecmatmulpacked-47ad.html#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="coopvecmatmulpacked-47ad.html#typeparam-T" class="code_type">T</a> : <a href="index.html" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopvecmatmulpacked-47ad.html#typeparam-U" class="code_type">U</a> : <a href="index.html" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 2:
<a href="index.html" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmulpacked-47ad.html#decl-M" class="code_var">M</a>&gt; <a href="coopvecmatmulpacked-47ad.html">coopVecMatMulPacked</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmulpacked-47ad.html#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmulpacked-47ad.html#decl-PackedK" class="code_var">PackedK</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmulpacked-47ad.html#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmulpacked-47ad.html#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>&gt;(
    <a href="index.html" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmulpacked-47ad.html#decl-PackedK" class="code_var">PackedK</a>&gt; <a href="coopvecmatmulpacked-47ad.html#decl-input" class="code_param">input</a>,
    <a href="index.html" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmulpacked-47ad.html#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmulpacked-47ad.html#decl-k" class="code_param">k</a>,
    <a href="index.html" class="code_type">RWStructuredBuffer</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>, <a href="index.html" class="code_type">DefaultDataLayout</a>&gt; <a href="coopvecmatmulpacked-47ad.html#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmulpacked-47ad.html#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="index.html" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmulpacked-47ad.html#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="index.html" class="code_type">CoopVecMatrixLayout</a> <a href="coopvecmatmulpacked-47ad.html#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="coopvecmatmulpacked-47ad.html#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="coopvecmatmulpacked-47ad.html#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="coopvecmatmulpacked-47ad.html#typeparam-T" class="code_type">T</a> : <a href="index.html" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopvecmatmulpacked-47ad.html#typeparam-U" class="code_type">U</a> : <a href="index.html" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 2:
<a href="index.html" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmulpacked-47ad.html#decl-M" class="code_var">M</a>&gt; <a href="coopvecmatmulpacked-47ad.html">coopVecMatMulPacked</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmulpacked-47ad.html#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmulpacked-47ad.html#decl-PackedK" class="code_var">PackedK</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmulpacked-47ad.html#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmulpacked-47ad.html#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>&gt;(
    <a href="index.html" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmulpacked-47ad.html#decl-PackedK" class="code_var">PackedK</a>&gt; <a href="coopvecmatmulpacked-47ad.html#decl-input" class="code_param">input</a>,
    <a href="index.html" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmulpacked-47ad.html#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmulpacked-47ad.html#decl-k" class="code_param">k</a>,
    <a href="index.html" class="code_type">StructuredBuffer</a>&lt;<a href="coopvecmatmulpacked-47ad.html#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>, <a href="index.html" class="code_type">DefaultDataLayout</a>&gt; <a href="coopvecmatmulpacked-47ad.html#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmulpacked-47ad.html#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="index.html" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmulpacked-47ad.html#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="index.html" class="code_type">CoopVecMatrixLayout</a> <a href="coopvecmatmulpacked-47ad.html#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="coopvecmatmulpacked-47ad.html#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="coopvecmatmulpacked-47ad.html#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="coopvecmatmulpacked-47ad.html#typeparam-T" class="code_type">T</a> : <a href="index.html" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopvecmatmulpacked-47ad.html#typeparam-U" class="code_type">U</a> : <a href="index.html" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index)
####  <a id="decl-M"></a>M  : int
####  <a id="decl-PackedK"></a>PackedK  : int
####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index)
####  <a id="typeparam-IgnoredBufferElementType"></a>IgnoredBufferElementType

## Parameters

####  <a id="decl-input"></a>input  : [CoopVec](../types/coopvec-04/index)\<U, PackedK\>
The input cooperative vector to multiply with the matrix.

####  <a id="decl-inputInterpretation"></a>inputInterpretation  : [CoopVecComponentType](../types/coopveccomponenttype-047g/index)
Specifies how to interpret the values in the input vector (e.g. as packed values).

####  <a id="decl-k"></a>k  : int
The number of columns in the matrix.

####  <a id="decl-matrix"></a>matrix  : [RWByteAddressBuffer](../types/rwbyteaddressbuffer-0126d/index)
The matrix buffer to multiply with.

####  <a id="decl-matrixOffset"></a>matrixOffset  : int
Byte offset into the matrix buffer.

####  <a id="decl-matrixInterpretation"></a>matrixInterpretation  : [CoopVecComponentType](../types/coopveccomponenttype-047g/index)
Specifies how to interpret the values in the matrix.

####  <a id="decl-memoryLayout"></a>memoryLayout  : [CoopVecMatrixLayout](../types/coopvecmatrixlayout-047d/index)
Specifies the memory layout of the matrix (row-major or column-major).

####  <a id="decl-transpose"></a>transpose  : bool
Whether to transpose the matrix before multiplication.

####  <a id="decl-matrixStride"></a>matrixStride  : uint
The stride between matrix rows/columns in bytes.

####  <a id="decl-matrix"></a>matrix  : [ByteAddressBuffer](../types/byteaddressbuffer-04b/index)
The matrix buffer to multiply with.

####  <a id="decl-matrix"></a>matrix  : [RWStructuredBuffer](../types/rwstructuredbuffer-012c/index)\<IgnoredBufferElementType, [DefaultDataLayout](../types/defaultdatalayout-07b/index)\>
The matrix buffer to multiply with.

####  <a id="decl-matrix"></a>matrix  : [StructuredBuffer](../types/structuredbuffer-0a/index)\<IgnoredBufferElementType, [DefaultDataLayout](../types/defaultdatalayout-07b/index)\>
The matrix buffer to multiply with.


## Return value
A new cooperative vector containing the result of the matrix multiplication.

## Remarks
Unlike coopVecMatMul, this function supports packed input interpretations where multiple values
can be packed into each element of the input vector. The k parameter specifies the actual number of
values to use from the packed input.


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


