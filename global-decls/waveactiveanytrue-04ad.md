---
layout: stdlib-reference
---

# WaveActiveAnyTrue

## Description





## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="waveactiveanytrue-04ad.md">WaveActiveAnyTrue</a>(<span class="code_keyword">bool</span> <a href="waveactiveanytrue-04ad.md#decl-condition" class="code_param">condition</a>);

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

Requires capability: `spvGroupNonUniformVote`.



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
