---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.matMulAddAccum

## Description

Performs matrix multiplication and accumulation with bias: this += input * matrix + bias



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="matmuladdaccum-369">matMulAddAccum</a>&lt;<a href="matmuladdaccum-369#typeparam-U" class="code_type">U</a>, <a href="matmuladdaccum-369#decl-K" class="code_var">K</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="matmuladdaccum-369#typeparam-U" class="code_type">U</a>, <a href="matmuladdaccum-369#decl-K" class="code_var">K</a>&gt; <a href="matmuladdaccum-369#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccum-369#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <a href="../types/rwbyteaddressbuffer-0126d/index" class="code_type">RWByteAddressBuffer</a> <a href="matmuladdaccum-369#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccum-369#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccum-369#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/rwbyteaddressbuffer-0126d/index" class="code_type">RWByteAddressBuffer</a> <a href="matmuladdaccum-369#decl-bias" class="code_param">bias</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccum-369#decl-biasOffset" class="code_param">biasOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccum-369#decl-biasInterpretation" class="code_param">biasInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index" class="code_type">CoopVecMatrixLayout</a> <a href="matmuladdaccum-369#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="matmuladdaccum-369#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="matmuladdaccum-369#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="matmuladdaccum-369#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<span class="code_keyword">void</span> <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="matmuladdaccum-369">matMulAddAccum</a>&lt;<a href="matmuladdaccum-369#typeparam-U" class="code_type">U</a>, <a href="matmuladdaccum-369#decl-K" class="code_var">K</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="matmuladdaccum-369#typeparam-U" class="code_type">U</a>, <a href="matmuladdaccum-369#decl-K" class="code_var">K</a>&gt; <a href="matmuladdaccum-369#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccum-369#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <a href="../types/byteaddressbuffer-04b/index" class="code_type">ByteAddressBuffer</a> <a href="matmuladdaccum-369#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccum-369#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccum-369#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/byteaddressbuffer-04b/index" class="code_type">ByteAddressBuffer</a> <a href="matmuladdaccum-369#decl-bias" class="code_param">bias</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccum-369#decl-biasOffset" class="code_param">biasOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccum-369#decl-biasInterpretation" class="code_param">biasInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index" class="code_type">CoopVecMatrixLayout</a> <a href="matmuladdaccum-369#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="matmuladdaccum-369#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="matmuladdaccum-369#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="matmuladdaccum-369#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index)
####  <a id="decl-K"></a>K  : int

## Parameters

####  <a id="decl-input"></a>input  : [CoopVec](../types/coopvec-04/index)\<U, K\>
The input vector to multiply with the matrix

####  <a id="decl-inputInterpretation"></a>inputInterpretation  : [CoopVecComponentType](../types/coopveccomponenttype-047g/index)
How to interpret the input vector elements (must not be packed)

####  <a id="decl-matrix"></a>matrix  : [RWByteAddressBuffer](../types/rwbyteaddressbuffer-0126d/index)
The matrix buffer to multiply with

####  <a id="decl-matrixOffset"></a>matrixOffset  : int
Byte offset into the matrix buffer

####  <a id="decl-matrixInterpretation"></a>matrixInterpretation  : [CoopVecComponentType](../types/coopveccomponenttype-047g/index)
How to interpret the matrix elements

####  <a id="decl-bias"></a>bias  : [RWByteAddressBuffer](../types/rwbyteaddressbuffer-0126d/index)
The bias buffer to add

####  <a id="decl-biasOffset"></a>biasOffset  : int
Byte offset into the bias buffer

####  <a id="decl-biasInterpretation"></a>biasInterpretation  : [CoopVecComponentType](../types/coopveccomponenttype-047g/index)
How to interpret the bias elements

####  <a id="decl-memoryLayout"></a>memoryLayout  : [CoopVecMatrixLayout](../types/coopvecmatrixlayout-047d/index)
Memory layout of the matrix (row or column major)

####  <a id="decl-transpose"></a>transpose  : bool
Whether to transpose the matrix before multiplication

####  <a id="decl-matrixStride"></a>matrixStride  : uint
Stride between matrix rows/columns in bytes

####  <a id="decl-matrix"></a>matrix  : [ByteAddressBuffer](../types/byteaddressbuffer-04b/index)
The matrix buffer to multiply with

####  <a id="decl-bias"></a>bias  : [ByteAddressBuffer](../types/byteaddressbuffer-04b/index)
The bias buffer to add


