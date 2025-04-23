---
layout: stdlib-reference
---

# GeometryIndex

## Description

Returns the index of the geometry that was hit in an intersection, any-hit, or closest-hit shader.



## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="geometryindex-08.md">GeometryIndex</a>();

</pre>

## Return value
Zero-based index of the geometry in the current instance

## Remarks
Available in intersection, any-hit, and closest-hit shaders


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `intersection`, `closesthit`, `anyhit`.

#### glsl
Available in stages: `intersection`, `closesthit`, `anyhit`.

#### spirv
Available in stages: `intersection`, `closesthit`, `anyhit`.

Requires capability: `spvRayTracingKHR`.



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
