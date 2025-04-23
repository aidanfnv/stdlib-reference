---
layout: stdlib-reference
---

# packInt4x8

## Description

Pack a vector of 4 signed 32/16 bit integers into a packed value of 4 8-bit integers, dropping unused bits.




## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="packint4x8-4.md">packInt4x8</a>(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, 4&gt; <a href="packint4x8-4.md#decl-unpackedValue" class="code_param">unpackedValue</a>);

<span class="code_keyword">uint</span> <a href="packint4x8-4.md">packInt4x8</a>(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;int16_t, 4&gt; <a href="packint4x8-4.md#decl-unpackedValue" class="code_param">unpackedValue</a>);

</pre>

## Parameters

####  <a id="decl-unpackedValue"></a>unpackedValue  : [vector](../types/vector/index.md)\<int, 4\>
####  <a id="decl-unpackedValue"></a>unpackedValue  : [vector](../types/vector/index.md)\<int16\_t, 4\>

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
