---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.matMulAccumPacked

## Description

Multiply the given input Cooperative vector with the given matrix and accumulate the result into this vector.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="matmulaccumpacked-36b">matMulAccumPacked</a>&lt;<a href="matmulaccumpacked-36b#typeparam-U" class="code_type">U</a>, <a href="matmulaccumpacked-36b#decl-PackedK" class="code_var">PackedK</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="matmulaccumpacked-36b#typeparam-U" class="code_type">U</a>, <a href="matmulaccumpacked-36b#decl-PackedK" class="code_var">PackedK</a>&gt; <a href="matmulaccumpacked-36b#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmulaccumpacked-36b#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <span class="code_keyword">int</span> <a href="matmulaccumpacked-36b#decl-k" class="code_param">k</a>,
    <a href="../types/rwbyteaddressbuffer-0126d/index" class="code_type">RWByteAddressBuffer</a> <a href="matmulaccumpacked-36b#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="matmulaccumpacked-36b#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmulaccumpacked-36b#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index" class="code_type">CoopVecMatrixLayout</a> <a href="matmulaccumpacked-36b#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="matmulaccumpacked-36b#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="matmulaccumpacked-36b#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="matmulaccumpacked-36b#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<span class="code_keyword">void</span> <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="matmulaccumpacked-36b">matMulAccumPacked</a>&lt;<a href="matmulaccumpacked-36b#typeparam-U" class="code_type">U</a>, <a href="matmulaccumpacked-36b#decl-PackedK" class="code_var">PackedK</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="matmulaccumpacked-36b#typeparam-U" class="code_type">U</a>, <a href="matmulaccumpacked-36b#decl-PackedK" class="code_var">PackedK</a>&gt; <a href="matmulaccumpacked-36b#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmulaccumpacked-36b#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <span class="code_keyword">int</span> <a href="matmulaccumpacked-36b#decl-k" class="code_param">k</a>,
    <a href="../types/byteaddressbuffer-04b/index" class="code_type">ByteAddressBuffer</a> <a href="matmulaccumpacked-36b#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="matmulaccumpacked-36b#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmulaccumpacked-36b#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index" class="code_type">CoopVecMatrixLayout</a> <a href="matmulaccumpacked-36b#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="matmulaccumpacked-36b#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="matmulaccumpacked-36b#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="matmulaccumpacked-36b#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index)
####  <a id="decl-PackedK"></a>PackedK  : int

## Parameters

####  <a id="decl-input"></a>input  : [CoopVec](../types/coopvec-04/index)\<U, PackedK\>
The input Cooperative vector to multiply with the matrix.

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


## Remarks
Unlike matMulAccum, this function supports packed input interpretations where multiple values
can be packed into each element of the input vector. The k parameter specifies the actual number of
values to use from the packed input.


