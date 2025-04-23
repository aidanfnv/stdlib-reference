---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.load

## Description

Load values from a byte-addressable buffer into a cooperative vector.



## Signature 

<pre>
/// Requires Capability Set 1:
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>&gt; <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="load.md">load</a>(
    <a href="../byteaddressbuffer-04b/index.md" class="code_type">ByteAddressBuffer</a> <a href="load.md#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">int</span> <a href="load.md#decl-byteOffset16ByteAligned" class="code_param">byteOffset16ByteAligned</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 1:
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>&gt; <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="load.md">load</a>(
    <a href="../rwbyteaddressbuffer-0126d/index.md" class="code_type">RWByteAddressBuffer</a> <a href="load.md#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">int</span> <a href="load.md#decl-byteOffset16ByteAligned" class="code_param">byteOffset16ByteAligned</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 1:
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>&gt; <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="load.md">load</a>(
    <a href="../structuredbuffer-0a/index.md" class="code_type">StructuredBuffer</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="../defaultdatalayout-07b/index.md" class="code_type">DefaultDataLayout</a>&gt; <a href="load.md#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">int</span> <a href="load.md#decl-byteOffset16ByteAligned" class="code_param">byteOffset16ByteAligned</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 2:
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>&gt; <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="load.md">load</a>(
    <a href="../rwstructuredbuffer-012c/index.md" class="code_type">RWStructuredBuffer</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="../defaultdatalayout-07b/index.md" class="code_type">DefaultDataLayout</a>&gt; <a href="load.md#decl-buffer" class="code_param">buffer</a>,
    <span class="code_keyword">int</span> <a href="load.md#decl-byteOffset16ByteAligned" class="code_param">byteOffset16ByteAligned</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 1:
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>&gt; <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="load.md">load</a>&lt;<a href="load.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <span class="code_keyword">const</span> <a href="index.md#typeparam-T" class="code_type">T</a>[M] <a href="load.md#decl-data" class="code_param">data</a>,
    <span class="code_keyword">int</span> <a href="load.md#decl-byteOffset16ByteAligned" class="code_param">byteOffset16ByteAligned</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-buffer"></a>buffer  : [ByteAddressBuffer](../byteaddressbuffer-04b/index.md)
The source buffer to load data from.

####  <a id="decl-byteOffset16ByteAligned"></a>byteOffset16ByteAligned  : int = 0
The byte offset from the start of the buffer. Must be 16-byte aligned.

####  <a id="decl-buffer"></a>buffer  : [RWByteAddressBuffer](../rwbyteaddressbuffer-0126d/index.md)
The source buffer to load data from.

####  <a id="decl-buffer"></a>buffer  : [StructuredBuffer](../structuredbuffer-0a/index.md)\<[T](../structuredbuffer-0a/index.md#typeparam-T), [DefaultDataLayout](../defaultdatalayout-07b/index.md)\>
The source buffer to load data from.

####  <a id="decl-buffer"></a>buffer  : [RWStructuredBuffer](../rwstructuredbuffer-012c/index.md)\<[T](../rwstructuredbuffer-012c/index.md#typeparam-T), [DefaultDataLayout](../defaultdatalayout-07b/index.md)\>
The source buffer to load data from.

####  <a id="decl-data"></a>data  : [T](index.md#typeparam-T) \[ M \]

## Return value
A new cooperative vector containing the loaded values.


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
