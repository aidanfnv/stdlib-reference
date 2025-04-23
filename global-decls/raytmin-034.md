---
layout: stdlib-reference
---

# RayTMin

## Description

Returns the minimum valid intersection distance for the current ray.



## Signature 

<pre>
<span class="code_keyword">float</span> <a href="raytmin-034.md">RayTMin</a>();

</pre>

## Return value
Minimum distance along the ray where intersections are considered

## Remarks
Used to prevent self-intersections and near-plane clipping


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `closesthit`, `anyhit`, `miss`, `intersection`.

#### glsl
Available in stages: `closesthit`, `anyhit`, `miss`, `intersection`.

#### cuda
Available in stages: `closesthit`, `anyhit`, `miss`, `intersection`.

#### spirv
Available in stages: `closesthit`, `anyhit`, `miss`, `intersection`.

Requires capability: `spvRayTracingKHR`.



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
