---
layout: stdlib-reference
---

# RayQuery\<rayFlagsGeneric:uint\>\.CandidateProceduralPrimitiveNonOpaque

## Description

Checks if the candidate procedural primitive is non-opaque.



## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="index.md" class="code_type">RayQuery</a>&lt;<a href="index.md#decl-rayFlagsGeneric" class="code_var">rayFlagsGeneric</a>:<span class="code_keyword">uint</span>&gt;.<a href="candidateproceduralprimitivenonopaque-09jsv.md">CandidateProceduralPrimitiveNonOpaque</a>();

</pre>

## Return value
true if the primitive is non-opaque and requires shader evaluation


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvRayQueryKHR`.



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
