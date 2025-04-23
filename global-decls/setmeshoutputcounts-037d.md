---
layout: stdlib-reference
---

# SetMeshOutputCounts

## Description

Set the number of output vertices and primitives for a mesh shader invocation.




## Signature 

<pre>
<span class="code_keyword">void</span> <a href="setmeshoutputcounts-037d.md">SetMeshOutputCounts</a>(
    <span class="code_keyword">uint</span> <a href="setmeshoutputcounts-037d.md#decl-vertexCount" class="code_param">vertexCount</a>,
    <span class="code_keyword">uint</span> <a href="setmeshoutputcounts-037d.md#decl-primitiveCount" class="code_param">primitiveCount</a>);

</pre>

## Parameters

####  <a id="decl-vertexCount"></a>vertexCount  : uint
####  <a id="decl-primitiveCount"></a>primitiveCount  : uint

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `amplification`, `mesh`.

#### glsl
Available in stages: `amplification`, `mesh`.

#### metal
Available in stages: `amplification`, `mesh`.

#### spirv
Available in stages: `amplification`, `mesh`.

Requires capability: `spvMeshShadingEXT`.



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
