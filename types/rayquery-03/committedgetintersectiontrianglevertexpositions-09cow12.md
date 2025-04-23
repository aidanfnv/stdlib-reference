---
layout: stdlib-reference
---

# RayQuery\<rayFlagsGeneric:uint\>\.CommittedGetIntersectionTriangleVertexPositions

## Description

Gets the triangle vertex positions for an intersection.



## Signature 

<pre>
<a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt;[3] <a href="index.md" class="code_type">RayQuery</a>&lt;<a href="index.md#decl-rayFlagsGeneric" class="code_var">rayFlagsGeneric</a>:<span class="code_keyword">uint</span>&gt;.<a href="committedgetintersectiontrianglevertexpositions-09cow12.md">CommittedGetIntersectionTriangleVertexPositions</a>();

</pre>

## Return value
Array of three vertex positions in world space

## Remarks
Requires ray query position fetch extension


## Availability and Requirements

Defined for the following targets:

#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvRayQueryPositionFetchKHR`.



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
