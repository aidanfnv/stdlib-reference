---
layout: stdlib-reference
---

# RayFlags

## Description

Returns the flags used when tracing the current ray.



## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="rayflags-03.md">RayFlags</a>();

</pre>

## Return value
Combination of RAY_FLAG values used for this ray

## Remarks
Allows shaders to modify behavior based on ray trace flags


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
