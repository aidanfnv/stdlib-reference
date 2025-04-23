---
layout: stdlib-reference
---

# WaveActiveCountBits

## Description





## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="waveactivecountbits-04af.md">WaveActiveCountBits</a>(<span class="code_keyword">bool</span> <a href="waveactivecountbits-04af.md#decl-value" class="code_param">value</a>);

</pre>

## Parameters

####  <a id="decl-value"></a>value  : bool

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

Requires capability: `spvGroupNonUniformBallot`.



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
