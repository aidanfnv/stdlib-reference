---
layout: stdlib-reference
---

# reversebits

## Description

Reverse order of bits.



## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="reversebits.md">reversebits</a>(<span class="code_keyword">uint</span> <a href="reversebits.md#decl-value" class="code_param">value</a>);

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="reversebits.md#decl-N" class="code_var">N</a>&gt; <a href="reversebits.md">reversebits</a>&lt;<a href="reversebits.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="reversebits.md#decl-N" class="code_var">N</a>&gt; <a href="reversebits.md#decl-value" class="code_param">value</a>);

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-value"></a>value  : uint
The value to reverse bits of.

####  <a id="decl-value"></a>value  : [vector](../types/vector/index.md)\<uint, [N](../types/vector/index.md#decl-N)\>
The value to reverse bits of.


## Return value
The bits of <span class='code'><a href="reversebits.md#decl-value" class="code_param">value</a></span>, reversed such that bit n of the result is equal to bit (width - 1 - n) of <span class='code'><a href="reversebits.md#decl-value" class="code_param">value</a></span>.

## Remarks
For SPIR-V, this function maps to <span class='code'>OpBitReverse</span>.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### wgsl
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
