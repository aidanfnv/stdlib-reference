---
layout: stdlib-reference
---

# RWByteAddressBuffer\.InterlockedAddI64

## Description

Perform a 64-bit integer atomic add operation at <span class='code'><a href="interlockedaddi64-0be.md#decl-byteAddress" class="code_param">byteAddress</a></span>.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="interlockedaddi64-0be.md">InterlockedAddI64</a>(
    <span class="code_keyword">uint</span> <a href="interlockedaddi64-0be.md#decl-byteAddress" class="code_param">byteAddress</a>,
    int64_t <a href="interlockedaddi64-0be.md#decl-valueToAdd" class="code_param">valueToAdd</a>,
    <span class="code_keyword">out</span> int64_t <a href="interlockedaddi64-0be.md#decl-originalValue" class="code_param">originalValue</a>);

<span class="code_keyword">void</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="interlockedaddi64-0be.md">InterlockedAddI64</a>(
    <span class="code_keyword">uint</span> <a href="interlockedaddi64-0be.md#decl-byteAddress" class="code_param">byteAddress</a>,
    int64_t <a href="interlockedaddi64-0be.md#decl-valueToAdd" class="code_param">valueToAdd</a>);

</pre>

## Parameters

####  <a id="decl-byteAddress"></a>byteAddress  : uint
The address at which to perform the atomic add operation.

####  <a id="decl-valueToAdd"></a>valueToAdd  : int64\_t
The value to add to the value at <span class='code'><a href="interlockedaddi64-0be.md#decl-byteAddress" class="code_param">byteAddress</a></span>.

####  <a id="decl-originalValue"></a>originalValue  : int64\_t
The original value at <span class='code'><a href="interlockedaddi64-0be.md#decl-byteAddress" class="code_param">byteAddress</a></span> before the add operation.


## Remarks
For SPIR-V, this function maps to <span class='code'>OpAtomicAdd</span>. For HLSL, this function
translates to <span class='code'><a href="interlockedadd64-0b.md">InterlockedAdd64</a></span> and requires shader model 6.6.
For CUDA, this function maps to <span class='code'>atomicAdd</span>.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvInt64Atomics`.



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
