---
layout: stdlib-reference
---

# coopVecLoadGroupshared

## Description





## Signature 

<pre>
<a href="../types/coopvec-04/index.md" class="code_type">CoopVec</a>&lt;<a href="coopvecloadgroupshared-47b.md#typeparam-T" class="code_type">T</a>, <a href="coopvecloadgroupshared-47b.md#decl-N" class="code_var">N</a>&gt; <a href="coopvecloadgroupshared-47b.md">coopVecLoadGroupshared</a>&lt;<a href="coopvecloadgroupshared-47b.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="coopvecloadgroupshared-47b.md#typeparam-T" class="code_type">T</a>, <a href="coopvecloadgroupshared-47b.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <span class="code_keyword">const</span> <a href="coopvecloadgroupshared-47b.md#typeparam-T" class="code_type">T</a>[<a href="coopvecloadgroupshared-47b.md#decl-M" class="code_var">M</a>] <a href="coopvecloadgroupshared-47b.md#decl-data" class="code_param">data</a>,
    <span class="code_keyword">int</span> <a href="coopvecloadgroupshared-47b.md#decl-byteOffset16ByteAligned" class="code_param">byteOffset16ByteAligned</a>)
    <span class='code_keyword'>where</span> <a href="coopvecloadgroupshared-47b.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int
####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index.md)
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-data"></a>data  : [T](coopvecloadgroupshared-47b.md#typeparam-T) \[ [M](coopvecloadgroupshared-47b.md#decl-M) \]
####  <a id="decl-byteOffset16ByteAligned"></a>byteOffset16ByteAligned  : int = 0

## Availability and Requirements

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
