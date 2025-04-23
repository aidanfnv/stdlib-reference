---
layout: stdlib-reference
---

# RWByteAddressBuffer\.\_NvInterlockedAddFp16x2

## Description



Maps to the <span class='code'>NvInterlockedAddFp16x2</span> NVAPI function.
Perform 2 16-bit floating point atomic add operations at <span class='code'><a href="0nvinterlockedaddfp16x2-013eh.md#decl-byteAddress" class="code_param">byteAddress</a></span>.

## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="0nvinterlockedaddfp16x2-013eh.md">_NvInterlockedAddFp16x2</a>(
    <span class="code_keyword">uint</span> <a href="0nvinterlockedaddfp16x2-013eh.md#decl-byteAddress" class="code_param">byteAddress</a>,
    <span class="code_keyword">uint</span> <a href="0nvinterlockedaddfp16x2-013eh.md#decl-fp16x2Value" class="code_param">fp16x2Value</a>);

</pre>

## Parameters

####  <a id="decl-byteAddress"></a>byteAddress  : uint
The address at which to perform the atomic add operation.

####  <a id="decl-fp16x2Value"></a>fp16x2Value  : uint
Two 16-bit floating point values are packed into a 32-bit unsigned integer.


## Return value
The 2 16-bit floating point values packed into a 32-bit unsigned integer.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.




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
