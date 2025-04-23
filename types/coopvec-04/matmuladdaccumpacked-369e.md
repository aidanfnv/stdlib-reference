---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.matMulAddAccumPacked

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="matmuladdaccumpacked-369e.md">matMulAddAccumPacked</a>&lt;<a href="matmuladdaccumpacked-369e.md#typeparam-U" class="code_type">U</a>, <a href="matmuladdaccumpacked-369e.md#decl-PackedK" class="code_var">PackedK</a>:<span class="code_keyword">int</span>&gt;(
    <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="matmuladdaccumpacked-369e.md#typeparam-U" class="code_type">U</a>, <a href="matmuladdaccumpacked-369e.md#decl-PackedK" class="code_var">PackedK</a>&gt; <a href="matmuladdaccumpacked-369e.md#decl-input" class="code_param">input</a>,
    <a href="../coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccumpacked-369e.md#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccumpacked-369e.md#decl-k" class="code_param">k</a>,
    <a href="../rwbyteaddressbuffer-0126d/index.md" class="code_type">RWByteAddressBuffer</a> <a href="matmuladdaccumpacked-369e.md#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccumpacked-369e.md#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccumpacked-369e.md#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../rwbyteaddressbuffer-0126d/index.md" class="code_type">RWByteAddressBuffer</a> <a href="matmuladdaccumpacked-369e.md#decl-bias" class="code_param">bias</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccumpacked-369e.md#decl-biasOffset" class="code_param">biasOffset</a>,
    <a href="../coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccumpacked-369e.md#decl-biasInterpretation" class="code_param">biasInterpretation</a>,
    <a href="../coopvecmatrixlayout-047d/index.md" class="code_type">CoopVecMatrixLayout</a> <a href="matmuladdaccumpacked-369e.md#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="matmuladdaccumpacked-369e.md#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="matmuladdaccumpacked-369e.md#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="matmuladdaccumpacked-369e.md#typeparam-U" class="code_type">U</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<span class="code_keyword">void</span> <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="matmuladdaccumpacked-369e.md">matMulAddAccumPacked</a>&lt;<a href="matmuladdaccumpacked-369e.md#typeparam-U" class="code_type">U</a>, <a href="matmuladdaccumpacked-369e.md#decl-PackedK" class="code_var">PackedK</a>:<span class="code_keyword">int</span>&gt;(
    <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="matmuladdaccumpacked-369e.md#typeparam-U" class="code_type">U</a>, <a href="matmuladdaccumpacked-369e.md#decl-PackedK" class="code_var">PackedK</a>&gt; <a href="matmuladdaccumpacked-369e.md#decl-input" class="code_param">input</a>,
    <a href="../coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccumpacked-369e.md#decl-inputInterpretation" class="code_param">inputInterpretation</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccumpacked-369e.md#decl-k" class="code_param">k</a>,
    <a href="../byteaddressbuffer-04b/index.md" class="code_type">ByteAddressBuffer</a> <a href="matmuladdaccumpacked-369e.md#decl-matrix" class="code_param">matrix</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccumpacked-369e.md#decl-matrixOffset" class="code_param">matrixOffset</a>,
    <a href="../coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccumpacked-369e.md#decl-matrixInterpretation" class="code_param">matrixInterpretation</a>,
    <a href="../byteaddressbuffer-04b/index.md" class="code_type">ByteAddressBuffer</a> <a href="matmuladdaccumpacked-369e.md#decl-bias" class="code_param">bias</a>,
    <span class="code_keyword">int</span> <a href="matmuladdaccumpacked-369e.md#decl-biasOffset" class="code_param">biasOffset</a>,
    <a href="../coopveccomponenttype-047g/index.md" class="code_type">CoopVecComponentType</a> <a href="matmuladdaccumpacked-369e.md#decl-biasInterpretation" class="code_param">biasInterpretation</a>,
    <a href="../coopvecmatrixlayout-047d/index.md" class="code_type">CoopVecMatrixLayout</a> <a href="matmuladdaccumpacked-369e.md#decl-memoryLayout" class="code_param">memoryLayout</a>,
    <span class="code_keyword">bool</span> <a href="matmuladdaccumpacked-369e.md#decl-transpose" class="code_param">transpose</a>,
    <span class="code_keyword">uint</span> <a href="matmuladdaccumpacked-369e.md#decl-matrixStride" class="code_param">matrixStride</a>)
    <span class='code_keyword'>where</span> <a href="matmuladdaccumpacked-369e.md#typeparam-U" class="code_type">U</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../../interfaces/0_builtinarithmetictype-029j/index.md)
####  <a id="decl-PackedK"></a>PackedK  : int

## Parameters

####  <a id="decl-input"></a>input  : [CoopVec](index.md)\<U, PackedK\>
####  <a id="decl-inputInterpretation"></a>inputInterpretation  : [CoopVecComponentType](../coopveccomponenttype-047g/index.md)
####  <a id="decl-k"></a>k  : int
####  <a id="decl-matrix"></a>matrix  : [RWByteAddressBuffer](../rwbyteaddressbuffer-0126d/index.md)
####  <a id="decl-matrixOffset"></a>matrixOffset  : int
####  <a id="decl-matrixInterpretation"></a>matrixInterpretation  : [CoopVecComponentType](../coopveccomponenttype-047g/index.md)
####  <a id="decl-bias"></a>bias  : [RWByteAddressBuffer](../rwbyteaddressbuffer-0126d/index.md)
####  <a id="decl-biasOffset"></a>biasOffset  : int
####  <a id="decl-biasInterpretation"></a>biasInterpretation  : [CoopVecComponentType](../coopveccomponenttype-047g/index.md)
####  <a id="decl-memoryLayout"></a>memoryLayout  : [CoopVecMatrixLayout](../coopvecmatrixlayout-047d/index.md)
####  <a id="decl-transpose"></a>transpose  : bool
####  <a id="decl-matrixStride"></a>matrixStride  : uint
####  <a id="decl-matrix"></a>matrix  : [ByteAddressBuffer](../byteaddressbuffer-04b/index.md)
####  <a id="decl-bias"></a>bias  : [ByteAddressBuffer](../byteaddressbuffer-04b/index.md)


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
