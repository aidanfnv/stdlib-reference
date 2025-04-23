---
layout: stdlib-reference
---

# unpackUnorm4x8ToFloat

## Description

Unpack a 32-bit unsigned integer into four 8-bit unsigned integers.
Then, each 8-bit value is converted to a normalized single-precision
floating-point value to generate a 4-component vector.




## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 4&gt; <a href="unpackunorm4x8tofloat-6eg.md">unpackUnorm4x8ToFloat</a>(<span class="code_keyword">uint</span> <a href="unpackunorm4x8tofloat-6eg.md#decl-packedValue" class="code_param">packedValue</a>);

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
