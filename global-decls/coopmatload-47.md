---
layout: stdlib-reference
---

# coopMatLoad

## Description





## Signature 

<pre>
<a href="../types/coopmat-04/index.md" class="code_type">CoopMat</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="coopmatload-47.md#decl-S" class="code_var">S</a>, <a href="coopmatload-47.md#decl-M" class="code_var">M</a>, <a href="coopmatload-47.md#decl-N" class="code_var">N</a>, <a href="coopmatload-47.md#decl-R" class="code_var">R</a>&gt; <a href="coopmatload-47.md">coopMatLoad</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="coopmatload-47.md#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index.md" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index.md" class="code_type">CoopMatMatrixUse</a>&gt;(
    <a href="../types/byteaddressbuffer-04b/index.md" class="code_type">ByteAddressBuffer</a> <a href="coopmatload-47.md#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">uint</span> <a href="coopmatload-47.md#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="coopmatload-47.md#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index.md" class="code_type">CoopMatMatrixLayout</a> <a href="coopmatload-47.md#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="coopmatload-47.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/coopmat-04/index.md" class="code_type">CoopMat</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="coopmatload-47.md#decl-S" class="code_var">S</a>, <a href="coopmatload-47.md#decl-M" class="code_var">M</a>, <a href="coopmatload-47.md#decl-N" class="code_var">N</a>, <a href="coopmatload-47.md#decl-R" class="code_var">R</a>&gt; <a href="coopmatload-47.md">coopMatLoad</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="coopmatload-47.md#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index.md" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index.md" class="code_type">CoopMatMatrixUse</a>&gt;(
    <a href="../types/rwbyteaddressbuffer-0126d/index.md" class="code_type">RWByteAddressBuffer</a> <a href="coopmatload-47.md#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">uint</span> <a href="coopmatload-47.md#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="coopmatload-47.md#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index.md" class="code_type">CoopMatMatrixLayout</a> <a href="coopmatload-47.md#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="coopmatload-47.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/coopmat-04/index.md" class="code_type">CoopMat</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="coopmatload-47.md#decl-S" class="code_var">S</a>, <a href="coopmatload-47.md#decl-M" class="code_var">M</a>, <a href="coopmatload-47.md#decl-N" class="code_var">N</a>, <a href="coopmatload-47.md#decl-R" class="code_var">R</a>&gt; <a href="coopmatload-47.md">coopMatLoad</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="coopmatload-47.md#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index.md" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index.md" class="code_type">CoopMatMatrixUse</a>&gt;(
    <a href="../types/structuredbuffer-0a/index.md" class="code_type">StructuredBuffer</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="../types/defaultdatalayout-07b/index.md" class="code_type">DefaultDataLayout</a>&gt; <a href="coopmatload-47.md#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">uint</span> <a href="coopmatload-47.md#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="coopmatload-47.md#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index.md" class="code_type">CoopMatMatrixLayout</a> <a href="coopmatload-47.md#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="coopmatload-47.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/coopmat-04/index.md" class="code_type">CoopMat</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="coopmatload-47.md#decl-S" class="code_var">S</a>, <a href="coopmatload-47.md#decl-M" class="code_var">M</a>, <a href="coopmatload-47.md#decl-N" class="code_var">N</a>, <a href="coopmatload-47.md#decl-R" class="code_var">R</a>&gt; <a href="coopmatload-47.md">coopMatLoad</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="coopmatload-47.md#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index.md" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index.md" class="code_type">CoopMatMatrixUse</a>&gt;(
    <a href="../types/rwstructuredbuffer-012c/index.md" class="code_type">RWStructuredBuffer</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="../types/defaultdatalayout-07b/index.md" class="code_type">DefaultDataLayout</a>&gt; <a href="coopmatload-47.md#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">uint</span> <a href="coopmatload-47.md#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="coopmatload-47.md#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index.md" class="code_type">CoopMatMatrixLayout</a> <a href="coopmatload-47.md#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="coopmatload-47.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/coopmat-04/index.md" class="code_type">CoopMat</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="coopmatload-47.md#decl-S" class="code_var">S</a>, <a href="coopmatload-47.md#decl-M" class="code_var">M</a>, <a href="coopmatload-47.md#decl-N" class="code_var">N</a>, <a href="coopmatload-47.md#decl-R" class="code_var">R</a>&gt; <a href="coopmatload-47.md">coopMatLoad</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="coopmatload-47.md#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index.md" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index.md" class="code_type">CoopMatMatrixUse</a>&gt;(
    <a href="../types/ptr-0/index.md" class="code_type">Ptr</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>&gt; <a href="coopmatload-47.md#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">uint</span> <a href="coopmatload-47.md#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="coopmatload-47.md#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index.md" class="code_type">CoopMatMatrixLayout</a> <a href="coopmatload-47.md#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="coopmatload-47.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/coopmat-04/index.md" class="code_type">CoopMat</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="coopmatload-47.md#decl-S" class="code_var">S</a>, <a href="coopmatload-47.md#decl-M" class="code_var">M</a>, <a href="coopmatload-47.md#decl-N" class="code_var">N</a>, <a href="coopmatload-47.md#decl-R" class="code_var">R</a>&gt; <a href="coopmatload-47.md">coopMatLoad</a>&lt;<a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>, <a href="coopmatload-47.md#decl-S" class="code_var">S</a>:<a href="../types/coopmatscope-047/index.md" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../types/coopmatmatrixuse-047d/index.md" class="code_type">CoopMatMatrixUse</a>, U:<span class="code_keyword">int</span>&gt;(
    <a href="coopmatload-47.md#typeparam-T" class="code_type">T</a>[<a href="coopmatload-47.md#decl-U" class="code_var">U</a>] <a href="coopmatload-47.md#decl-data" class="code_param">data</a>,
    <span class="code_keyword">uint</span> <a href="coopmatload-47.md#decl-element" class="code_param">element</a>,
    <span class="code_keyword">uint</span> <a href="coopmatload-47.md#decl-stride" class="code_param">stride</a>,
    <a href="../types/coopmatmatrixlayout-047d/index.md" class="code_type">CoopMatMatrixLayout</a> <a href="coopmatload-47.md#decl-matrixLayout" class="code_param">matrixLayout</a>)
    <span class='code_keyword'>where</span> <a href="coopmatload-47.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index.md)
####  <a id="decl-S"></a>S  : [CoopMatScope](../types/coopmatscope-047/index.md)
####  <a id="decl-M"></a>M  : int
####  <a id="decl-N"></a>N  : int
####  <a id="decl-R"></a>R  : [CoopMatMatrixUse](../types/coopmatmatrixuse-047d/index.md)
####  <a id="decl-U"></a>U  : int

## Parameters

####  <a id="decl-buffer"></a>buffer  : [ByteAddressBuffer](../types/byteaddressbuffer-04b/index.md)
####  <a id="decl-element"></a>element  : uint
####  <a id="decl-stride"></a>stride  : uint
####  <a id="decl-matrixLayout"></a>matrixLayout  : [CoopMatMatrixLayout](../types/coopmatmatrixlayout-047d/index.md)
####  <a id="decl-buffer"></a>buffer  : [RWByteAddressBuffer](../types/rwbyteaddressbuffer-0126d/index.md)
####  <a id="decl-buffer"></a>buffer  : [StructuredBuffer](../types/structuredbuffer-0a/index.md)\<[T](../types/structuredbuffer-0a/index.md#typeparam-T), [DefaultDataLayout](../types/defaultdatalayout-07b/index.md)\>
####  <a id="decl-buffer"></a>buffer  : [RWStructuredBuffer](../types/rwstructuredbuffer-012c/index.md)\<[T](../types/rwstructuredbuffer-012c/index.md#typeparam-T), [DefaultDataLayout](../types/defaultdatalayout-07b/index.md)\>
####  <a id="decl-buffer"></a>buffer  : [Ptr](../types/ptr-0/index.md)\<[T](../types/ptr-0/index.md#typeparam-T)\>
####  <a id="decl-data"></a>data  : [T](coopmatload-47.md#typeparam-T) \[ [U](coopmatload-47.md#decl-U) \]

## Availability and Requirements

Defined for the following targets:

#### spirv
Available in all stages.

Requires capability: `spvCooperativeMatrixKHR`.



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
