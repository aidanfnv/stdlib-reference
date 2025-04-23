---
layout: stdlib-reference
---

# DispatchRaysDimensions

## Description

Returns the dimensions of the ray dispatch.



## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 3&gt; <a href="dispatchraysdimensions-08c.md">DispatchRaysDimensions</a>();

</pre>

## Return value
3D dimensions of the ray dispatch grid

## Remarks
Available in all ray tracing shader stages


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `raygen`, `intersection`, `miss`, `callable`, `closesthit`, `anyhit`.

#### glsl
Available in stages: `raygen`, `intersection`, `miss`, `callable`, `closesthit`, `anyhit`.

#### cuda
Available in stages: `raygen`, `intersection`, `miss`, `callable`, `closesthit`, `anyhit`.

#### spirv
Available in stages: `raygen`, `intersection`, `miss`, `callable`, `closesthit`, `anyhit`.

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
