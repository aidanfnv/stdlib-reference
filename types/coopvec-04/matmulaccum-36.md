---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.matMulAccum

## Description

Accumulate the result from a matrix multiplication between an input Cooperative vector and a matrix.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="matmulaccum-36.md">matMulAccum</a>&lt;<a href="matmulaccum-36.md#typeparam-U" class="code_type">U</a>, <a href="matmulaccum-36.md#decl-K" class="code_var">K</a>:<span class="code_keyword">int</span>&gt;(
    <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="matmulaccum-36.md#typeparam-U" class="code_type">U</a>, <a href="matmulaccum-36.md#decl-K" class="code_var">K</a>&gt; <a href="matmulaccum-36.md#decl-input" class="code_param">input</a>,
    <a href="../coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="matmulaccum-36.md#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <a href="../rwbyteaddressbuffer-0126d/index.md" class="code_type">RWByteAddressBuffer</a> <a href="matmulaccum-36.md#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="matmulaccum-36.md#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="matmulaccum-36.md#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../coopvecmatrixlayout-047d/index.md" class="code_type">CoopVecMatrixLayout</a> <a href="matmulaccum-36.md#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="matmulaccum-36.md#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="matmulaccum-36.md#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="matmulaccum-36.md#typeparam-U" class="code_type">U</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<span class="code_keyword">void</span> <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="matmulaccum-36.md">matMulAccum</a>&lt;<a href="matmulaccum-36.md#typeparam-U" class="code_type">U</a>, <a href="matmulaccum-36.md#decl-K" class="code_var">K</a>:<span class="code_keyword">int</span>&gt;(
    <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="matmulaccum-36.md#typeparam-U" class="code_type">U</a>, <a href="matmulaccum-36.md#decl-K" class="code_var">K</a>&gt; <a href="matmulaccum-36.md#decl-input" class="code_param">input</a>,
    <a href="../coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="matmulaccum-36.md#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <a href="../byteaddressbuffer-04b/index.md" class="code_type">ByteAddressBuffer</a> <a href="matmulaccum-36.md#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="matmulaccum-36.md#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="matmulaccum-36.md#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../coopvecmatrixlayout-047d/index.md" class="code_type">CoopVecMatrixLayout</a> <a href="matmulaccum-36.md#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="matmulaccum-36.md#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="matmulaccum-36.md#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="matmulaccum-36.md#typeparam-U" class="code_type">U</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../../interfaces/0_builtinarithmetictype-029j/index.md)
####  <a id="decl-K"></a>K  : int

## Parameters

####  <a id="decl-input"></a>input  : [CoopVec](index.md)\<U, K\>
The input Cooperative vector to multiply with the matrix.

####  <a id="decl-inputInterpretation"></a>inputInterpretation  : [CoopVecComponentType](../coopveccomponenttype-047g/index.md)
Specifies how to interpret the values in the input vector (e.g. as 8-bit integers, 16-bit floats, etc).

####  <a id="decl-matrix"></a>matrix  : [RWByteAddressBuffer](../rwbyteaddressbuffer-0126d/index.md)
The matrix to multiply with the input vector.

####  <a id="decl-matrixOffset"></a>matrixOffset  : int
Byte offset into the matrix buffer.

####  <a id="decl-matrixInterpretation"></a>matrixInterpretation  : [CoopVecComponentType](../coopveccomponenttype-047g/index.md)
Specifies how to interpret the values in the matrix (e.g. as 8-bit integers, 16-bit floats, etc).

####  <a id="decl-memoryLayout"></a>memoryLayout  : [CoopVecMatrixLayout](../coopvecmatrixlayout-047d/index.md)
Specifies the memory layout of the matrix (row-major or column-major).

####  <a id="decl-transpose"></a>transpose  : bool
Whether to transpose the matrix before multiplication.

####  <a id="decl-matrixStride"></a>matrixStride  : uint
The stride in bytes between rows/columns of the matrix.

####  <a id="decl-matrix"></a>matrix  : [ByteAddressBuffer](../byteaddressbuffer-04b/index.md)
The matrix to multiply with the input vector.



<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      const href = link.getAttribute('href');
      if (href && href.includes('.md')) {
        // This regex will handle .md links with or without fragment identifiers or query parameters
        link.href = link.href.replace(/(.+)\.md(#[^?]*)?(\?.*)?$/, '$1.html$2$3');
      }
    });
  });
}
</script>
