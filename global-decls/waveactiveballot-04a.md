---
layout: stdlib-reference
---

# WaveActiveBallot

## Description





## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="waveactiveballot-04a.md">WaveActiveBallot</a>(<span class="code_keyword">bool</span> <a href="waveactiveballot-04a.md#decl-condition" class="code_param">condition</a>);

</pre>

## Parameters

####  <a id="decl-condition"></a>condition  : bool

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### wgsl
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
