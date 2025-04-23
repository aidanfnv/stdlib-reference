---
layout: stdlib-reference
---

# RWByteAddressBuffer\.InterlockedExchangeU64

## Description

Perform a 64-bit unsigned integer atomic exchange operation at <span class='code'><a href="interlockedexchangeu64-0bj.md#decl-byteAddress" class="code_param">byteAddress</a></span>.



## Signature 

<pre>
uint64_t <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="interlockedexchangeu64-0bj.md">InterlockedExchangeU64</a>(
    <span class="code_keyword">uint</span> <a href="interlockedexchangeu64-0bj.md#decl-byteAddress" class="code_param">byteAddress</a>,
    uint64_t <a href="interlockedexchangeu64-0bj.md#decl-value" class="code_param">value</a>);

</pre>

## Parameters

####  <a id="decl-byteAddress"></a>byteAddress  : uint
The address at which to perform the atomic exchange operation.

####  <a id="decl-value"></a>value  : uint64\_t
The operand for the exchange operation.


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
