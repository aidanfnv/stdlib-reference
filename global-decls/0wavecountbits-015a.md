---
layout: stdlib-reference
---

# \_WaveCountBits

## Description





## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="0wavecountbits-015a.md">_WaveCountBits</a>(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="0wavecountbits-015a.md#decl-value" class="code_param">value</a>);

</pre>

## Parameters

####  <a id="decl-value"></a>value  : [vector](../types/vector/index.md)\<uint, 4\>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvGroupNonUniformBallot`.
#### cuda
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
