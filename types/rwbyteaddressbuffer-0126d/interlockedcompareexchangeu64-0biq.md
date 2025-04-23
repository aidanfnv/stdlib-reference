---
layout: stdlib-reference
---

# RWByteAddressBuffer\.InterlockedCompareExchangeU64

## Description

Perform a 64-bit integer atomic compare-and-exchange operation at <span class='code'><a href="interlockedcompareexchangeu64-0biq.md#decl-byteAddress" class="code_param">byteAddress</a></span>.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="interlockedcompareexchangeu64-0biq.md">InterlockedCompareExchangeU64</a>(
    <span class="code_keyword">uint</span> <a href="interlockedcompareexchangeu64-0biq.md#decl-byteAddress" class="code_param">byteAddress</a>,
    uint64_t <a href="interlockedcompareexchangeu64-0biq.md#decl-compareValue" class="code_param">compareValue</a>,
    uint64_t <a href="interlockedcompareexchangeu64-0biq.md#decl-value" class="code_param">value</a>,
    <span class="code_keyword">out</span> uint64_t <a href="interlockedcompareexchangeu64-0biq.md#decl-outOriginalValue" class="code_param">outOriginalValue</a>);

</pre>

## Parameters

####  <a id="decl-byteAddress"></a>byteAddress  : uint
The address at which to perform the atomic compare-and-exchange operation.

####  <a id="decl-compareValue"></a>compareValue  : uint64\_t
The value to compare to the value at <span class='code'><a href="interlockedcompareexchangeu64-0biq.md#decl-byteAddress" class="code_param">byteAddress</a></span>.

####  <a id="decl-value"></a>value  : uint64\_t
The value to store at <span class='code'><a href="interlockedcompareexchangeu64-0biq.md#decl-byteAddress" class="code_param">byteAddress</a></span> if the comparison is successful.

####  <a id="decl-outOriginalValue"></a>outOriginalValue  : uint64\_t
The original value at <span class='code'><a href="interlockedcompareexchangeu64-0biq.md#decl-byteAddress" class="code_param">byteAddress</a></span> before the add operation.


## Remarks
For SPIR-V, this function maps to <span class='code'>OpAtomicCompareExchange</span>. For HLSL, this function
translates to <span class='code'><a href="interlockedcompareexchange64-0bi.md">InterlockedCompareExchange64</a></span> and requires shader model 6.6.
For CUDA, this function maps to <span class='code'>atomicCAS</span>.


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
      const href = link.getAttribute('href');
      if (href && href.includes('.md')) {
        // This regex will handle .md links with or without fragment identifiers or query parameters
        link.href = link.href.replace(/(.+)\.md(#[^?]*)?(\?.*)?$/, '$1.html$2$3');
      }
    });
  });
}
</script>
