---
layout: stdlib-reference
---

# ReorderThread

## Description

Reorders threads based on a coherence hint value. NumCoherenceHintBits indicates how many of
the least significant bits of CoherenceHint should be considered during reordering (max: 16).
Applications should set this to the lowest value required to represent all possible values in
CoherenceHint. For best performance, all threads should provide the same value for
NumCoherenceHintBits.
Where possible, reordering will also attempt to retain locality in the thread429496726642949671684294967193s launch indices
(DispatchRaysIndex in DXR).




## Signature 

<pre>
<span class="code_keyword">void</span> <a href="reorderthread-07.md">ReorderThread</a>(
    <span class="code_keyword">uint</span> <a href="reorderthread-07.md#decl-CoherenceHint" class="code_param">CoherenceHint</a>,
    <span class="code_keyword">uint</span> <a href="reorderthread-07.md#decl-NumCoherenceHintBitsFromLSB" class="code_param">NumCoherenceHintBitsFromLSB</a>);

<span class="code_keyword">void</span> <a href="reorderthread-07.md">ReorderThread</a>(
    <a href="../types/hitobject-03/index.md" class="code_type">HitObject</a> <a href="reorderthread-07.md#decl-HitOrMiss" class="code_param">HitOrMiss</a>,
    <span class="code_keyword">uint</span> <a href="reorderthread-07.md#decl-CoherenceHint" class="code_param">CoherenceHint</a>,
    <span class="code_keyword">uint</span> <a href="reorderthread-07.md#decl-NumCoherenceHintBitsFromLSB" class="code_param">NumCoherenceHintBitsFromLSB</a>);

<span class="code_keyword">void</span> <a href="reorderthread-07.md">ReorderThread</a>(<a href="../types/hitobject-03/index.md" class="code_type">HitObject</a> <a href="reorderthread-07.md#decl-HitOrMiss" class="code_param">HitOrMiss</a>);

</pre>

## Parameters

####  <a id="decl-CoherenceHint"></a>CoherenceHint  : uint
####  <a id="decl-NumCoherenceHintBitsFromLSB"></a>NumCoherenceHintBitsFromLSB  : uint
####  <a id="decl-HitOrMiss"></a>HitOrMiss  : [HitObject](../types/hitobject-03/index.md)

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in `raygen` stage only.

Requires capability: `hlsl_nvapi`.
#### glsl
Available in `raygen` stage only.

#### spirv
Available in `raygen` stage only.

Requires capabilities: `spvRayTracingKHR`, `spvShaderInvocationReorderNV`.



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
