---
layout: stdlib-reference
---

# HitTriangleVertexPosition

## Description

Get the vertex positions of the currently hit triangle in any-hit or closest-hit shader.
https://github.com/KhronosGroup/GLSL/blob/master/extensions/ext/GLSL_EXT_ray_tracing_position_fetch.txt



## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="hittrianglevertexposition-03bh.md">HitTriangleVertexPosition</a>(<span class="code_keyword">uint</span> <a href="hittrianglevertexposition-03bh.md#decl-index" class="code_param">index</a>);

</pre>

## Parameters

####  <a id="decl-index"></a>index  : uint
Index of the vertex (0-2)


## Return value
World-space position of the specified vertex

## Remarks
Requires ray tracing position fetch extension

## Availability and Requirements

Defined for the following targets:

#### glsl
Available in stages: `closesthit`, `anyhit`.

#### spirv
Available in stages: `closesthit`, `anyhit`.

Requires capability: `spvRayTracingPositionFetchKHR`.


## See Also
GL_EXT_ray_tracing_position_fetch



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
