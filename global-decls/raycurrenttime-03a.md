---
layout: stdlib-reference
---

# RayCurrentTime

## Description

Returns the current time value for motion blur.



## Signature 

<pre>
<span class="code_keyword">float</span> <a href="raycurrenttime-03a.md">RayCurrentTime</a>();

</pre>

## Return value
Time value between 0 and 1 for motion blur interpolation

## Remarks
Available when motion blur extension is enabled


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `closesthit`, `anyhit`, `miss`, `intersection`.

Requires capability: `hlsl_nvapi`.
#### glsl
Available in stages: `closesthit`, `anyhit`, `miss`, `intersection`.

#### spirv
Available in stages: `closesthit`, `anyhit`, `miss`, `intersection`.

Requires capabilities: `spvRayTracingMotionBlurNV`, `spvRayTracingKHR`.



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
