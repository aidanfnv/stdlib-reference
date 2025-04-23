---
layout: stdlib-reference
---

# RWByteAddressBuffer\.GetDimensions

## Description

Get the number of bytes in the buffer.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="getdimensions-03.md">GetDimensions</a>(<span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="getdimensions-03.md#decl-dim" class="code_param">dim</a>);

</pre>

## Parameters

####  <a id="decl-dim"></a>dim  : uint
\[out\] The number of bytes in the buffer.


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
