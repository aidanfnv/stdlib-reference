---
layout: stdlib-reference
---

# unpackUint4x8ToUint16

## Description

Unpack 4 unsigned 8-bit values into a vector of 16 bit integers.




## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;uint16_t, 4&gt; <a href="unpackuint4x8touint16-6df.md">unpackUint4x8ToUint16</a>(<span class="code_keyword">uint</span> <a href="unpackuint4x8touint16-6df.md#decl-packedValue" class="code_param">packedValue</a>);

</pre>

## Parameters

####  <a id="decl-packedValue"></a>packedValue  : uint

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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
