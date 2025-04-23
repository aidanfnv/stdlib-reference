---
layout: stdlib-reference
---

# coopVecMatMul

## Description

Multiply a cooperative vector with a matrix.



## Signature 

<pre>
/// Requires Capability Set 1:
<a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmul-47a.md#decl-M" class="code_var">M</a>&gt; <a href="coopvecmatmul-47a.md">coopVecMatMul</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmul-47a.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmul-47a.md#decl-K" class="code_var">K</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmul-47a.md#typeparam-U" class="code_type">U</a>&gt;(
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmul-47a.md#decl-K" class="code_var">K</a>&gt; <a href="coopvecmatmul-47a.md#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmul-47a.md#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <a href="../types/rwbyteaddressbuffer-0126d/index.md" class="code_type">RWByteAddressBuffer</a> <a href="coopvecmatmul-47a.md#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmul-47a.md#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmul-47a.md#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index.md" class="code_type">CoopVecMatrixLayout</a> <a href="coopvecmatmul-47a.md#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="coopvecmatmul-47a.md#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="coopvecmatmul-47a.md#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="coopvecmatmul-47a.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopvecmatmul-47a.md#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 1:
<a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmul-47a.md#decl-M" class="code_var">M</a>&gt; <a href="coopvecmatmul-47a.md">coopVecMatMul</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmul-47a.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmul-47a.md#decl-K" class="code_var">K</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmul-47a.md#typeparam-U" class="code_type">U</a>&gt;(
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmul-47a.md#decl-K" class="code_var">K</a>&gt; <a href="coopvecmatmul-47a.md#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmul-47a.md#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <a href="../types/byteaddressbuffer-04b/index.md" class="code_type">ByteAddressBuffer</a> <a href="coopvecmatmul-47a.md#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmul-47a.md#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmul-47a.md#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index.md" class="code_type">CoopVecMatrixLayout</a> <a href="coopvecmatmul-47a.md#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="coopvecmatmul-47a.md#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="coopvecmatmul-47a.md#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="coopvecmatmul-47a.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopvecmatmul-47a.md#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 2:
<a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmul-47a.md#decl-M" class="code_var">M</a>&gt; <a href="coopvecmatmul-47a.md">coopVecMatMul</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmul-47a.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmul-47a.md#decl-K" class="code_var">K</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmul-47a.md#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmul-47a.md#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>&gt;(
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmul-47a.md#decl-K" class="code_var">K</a>&gt; <a href="coopvecmatmul-47a.md#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmul-47a.md#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <a href="../types/rwstructuredbuffer-012c/index.md" class="code_type">RWStructuredBuffer</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>, <a href="../types/defaultdatalayout-07b/index.md" class="code_type">DefaultDataLayout</a>&gt; <a href="coopvecmatmul-47a.md#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmul-47a.md#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmul-47a.md#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index.md" class="code_type">CoopVecMatrixLayout</a> <a href="coopvecmatmul-47a.md#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="coopvecmatmul-47a.md#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="coopvecmatmul-47a.md#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="coopvecmatmul-47a.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopvecmatmul-47a.md#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 2:
<a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmul-47a.md#decl-M" class="code_var">M</a>&gt; <a href="coopvecmatmul-47a.md">coopVecMatMul</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-T" class="code_type">T</a>, <a href="coopvecmatmul-47a.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmul-47a.md#decl-K" class="code_var">K</a>:<span class="code_keyword">int</span>, <a href="coopvecmatmul-47a.md#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmul-47a.md#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>&gt;(
    <a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-U" class="code_type">U</a>, <a href="coopvecmatmul-47a.md#decl-K" class="code_var">K</a>&gt; <a href="coopvecmatmul-47a.md#decl-input" class="code_param">input</a>,
    <a href="../types/coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmul-47a.md#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <a href="../types/structuredbuffer-0a/index.md" class="code_type">StructuredBuffer</a>&lt;<a href="coopvecmatmul-47a.md#typeparam-IgnoredBufferElementType" class="code_type">IgnoredBufferElementType</a>, <a href="../types/defaultdatalayout-07b/index.md" class="code_type">DefaultDataLayout</a>&gt; <a href="coopvecmatmul-47a.md#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="coopvecmatmul-47a.md#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../types/coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="coopvecmatmul-47a.md#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../types/coopvecmatrixlayout-047d/index.md" class="code_type">CoopVecMatrixLayout</a> <a href="coopvecmatmul-47a.md#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="coopvecmatmul-47a.md#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="coopvecmatmul-47a.md#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="coopvecmatmul-47a.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="coopvecmatmul-47a.md#typeparam-U" class="code_type">U</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index.md)
####  <a id="decl-M"></a>M  : int
####  <a id="decl-K"></a>K  : int
####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index.md)
####  <a id="typeparam-IgnoredBufferElementType"></a>IgnoredBufferElementType

## Parameters

####  <a id="decl-input"></a>input  : [CoopVec](../types/coopvec-04/index.md)\<U, K\>
The input cooperative vector to multiply with the matrix.

####  <a id="decl-inputInterpretation"></a>inputInterpretation  : [CoopVecComponentType](../types/coopveccomponenttype-047g/index.md)
Specifies how to interpret the values in the input vector (e.g. as 8-bit integers, 16-bit floats, etc).

####  <a id="decl-matrix"></a>matrix  : [RWByteAddressBuffer](../types/rwbyteaddressbuffer-0126d/index.md)
The matrix to multiply with the input vector.

####  <a id="decl-matrixOffset"></a>matrixOffset  : int
Byte offset into the matrix buffer.

####  <a id="decl-matrixInterpretation"></a>matrixInterpretation  : [CoopVecComponentType](../types/coopveccomponenttype-047g/index.md)
Specifies how to interpret the values in the matrix (e.g. as 8-bit integers, 16-bit floats, etc).

####  <a id="decl-memoryLayout"></a>memoryLayout  : [CoopVecMatrixLayout](../types/coopvecmatrixlayout-047d/index.md)
Specifies the memory layout of the matrix (row-major or column-major).

####  <a id="decl-transpose"></a>transpose  : bool
Whether to transpose the matrix before multiplication.

####  <a id="decl-matrixStride"></a>matrixStride  : uint
The stride in bytes between rows/columns of the matrix.

####  <a id="decl-matrix"></a>matrix  : [ByteAddressBuffer](../types/byteaddressbuffer-04b/index.md)
The matrix to multiply with the input vector.

####  <a id="decl-matrix"></a>matrix  : [RWStructuredBuffer](../types/rwstructuredbuffer-012c/index.md)\<IgnoredBufferElementType, [DefaultDataLayout](../types/defaultdatalayout-07b/index.md)\>
The matrix to multiply with the input vector.

####  <a id="decl-matrix"></a>matrix  : [StructuredBuffer](../types/structuredbuffer-0a/index.md)\<IgnoredBufferElementType, [DefaultDataLayout](../types/defaultdatalayout-07b/index.md)\>
The matrix to multiply with the input vector.


## Return value
A new cooperative vector containing the result of the matrix multiplication.


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



<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
