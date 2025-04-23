---
layout: stdlib-reference
---

# RayQuery\<rayFlagsGeneric:uint\>\.CandidateWorldToObject4x3

## Description

Gets the world-to-object transform as a 4x3 matrix.



## Signature 

<pre>
<a href="../matrix/index.md" class="code_type">matrix</a>&lt;<span class="code_keyword">float</span>, 4, 3&gt; <a href="index.md" class="code_type">RayQuery</a>&lt;<a href="index.md#decl-rayFlagsGeneric" class="code_var">rayFlagsGeneric</a>:<span class="code_keyword">uint</span>&gt;.<a href="candidateworldtoobject4x3-09eg.md">CandidateWorldToObject4x3</a>();

</pre>

## Return value
4x3 matrix transforming from world to object space

## Remarks
Available for both candidate and committed hits


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
