---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.matMulAddAccumPacked

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="matmuladdaccumpacked-369e">matMulAddAccumPacked</a>&lt;<a href="matmuladdaccumpacked-369e#typeparam-U" class="code_type">U</a>, <a href="matmuladdaccumpacked-369e#decl-PackedK" class="code_var">PackedK</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="matmuladdaccumpacked-369e#typeparam-U" class="code_type">U</a>, <a href="matmuladdaccumpacked-369e#decl-PackedK" class="code_var">PackedK</a>&gt; <a href="matmuladdaccumpacked-369e#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccumpacked-369e#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccumpacked-369e#decl-k" class="code_param">k</a>,
    <a href="../types/rwbyteaddressbuffer-0126d/index" class="code_type">RWByteAddressBuffer</a> <a href="matmuladdaccumpacked-369e#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccumpacked-369e#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccumpacked-369e#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/rwbyteaddressbuffer-0126d/index" class="code_type">RWByteAddressBuffer</a> <a href="matmuladdaccumpacked-369e#decl-bias" class="code_param">bias</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccumpacked-369e#decl-biasOffset" class="code_param">biasOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccumpacked-369e#decl-biasInterpretation" class="code_param">biasInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index" class="code_type">CoopVecMatrixLayout</a> <a href="matmuladdaccumpacked-369e#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="matmuladdaccumpacked-369e#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="matmuladdaccumpacked-369e#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="matmuladdaccumpacked-369e#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

<span class="code_keyword">void</span> <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="matmuladdaccumpacked-369e">matMulAddAccumPacked</a>&lt;<a href="matmuladdaccumpacked-369e#typeparam-U" class="code_type">U</a>, <a href="matmuladdaccumpacked-369e#decl-PackedK" class="code_var">PackedK</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="matmuladdaccumpacked-369e#typeparam-U" class="code_type">U</a>, <a href="matmuladdaccumpacked-369e#decl-PackedK" class="code_var">PackedK</a>&gt; <a href="matmuladdaccumpacked-369e#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccumpacked-369e#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccumpacked-369e#decl-k" class="code_param">k</a>,
    <a href="../types/byteaddressbuffer-04b/index" class="code_type">ByteAddressBuffer</a> <a href="matmuladdaccumpacked-369e#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccumpacked-369e#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccumpacked-369e#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/byteaddressbuffer-04b/index" class="code_type">ByteAddressBuffer</a> <a href="matmuladdaccumpacked-369e#decl-bias" class="code_param">bias</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccumpacked-369e#decl-biasOffset" class="code_param">biasOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccumpacked-369e#decl-biasInterpretation" class="code_param">biasInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index" class="code_type">CoopVecMatrixLayout</a> <a href="matmuladdaccumpacked-369e#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="matmuladdaccumpacked-369e#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="matmuladdaccumpacked-369e#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="matmuladdaccumpacked-369e#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index)
####  <a id="decl-PackedK"></a>PackedK  : int

## Parameters

####  <a id="decl-input"></a>input  : [CoopVec](../types/coopvec-04/index)\<U, PackedK\>
####  <a id="decl-inputInterpretation"></a>inputInterpretation  : [CoopVecComponentType](../types/coopveccomponenttype-047g/index)
####  <a id="decl-k"></a>k  : int
####  <a id="decl-matrix"></a>matrix  : [RWByteAddressBuffer](../types/rwbyteaddressbuffer-0126d/index)
####  <a id="decl-matrixOffset"></a>matrixOffset  : int
####  <a id="decl-matrixInterpretation"></a>matrixInterpretation  : [CoopVecComponentType](../types/coopveccomponenttype-047g/index)
####  <a id="decl-bias"></a>bias  : [RWByteAddressBuffer](../types/rwbyteaddressbuffer-0126d/index)
####  <a id="decl-biasOffset"></a>biasOffset  : int
####  <a id="decl-biasInterpretation"></a>biasInterpretation  : [CoopVecComponentType](../types/coopveccomponenttype-047g/index)
####  <a id="decl-memoryLayout"></a>memoryLayout  : [CoopVecMatrixLayout](../types/coopvecmatrixlayout-047d/index)
####  <a id="decl-transpose"></a>transpose  : bool
####  <a id="decl-matrixStride"></a>matrixStride  : uint
####  <a id="decl-matrix"></a>matrix  : [ByteAddressBuffer](../types/byteaddressbuffer-04b/index)
####  <a id="decl-bias"></a>bias  : [ByteAddressBuffer](../types/byteaddressbuffer-04b/index)

