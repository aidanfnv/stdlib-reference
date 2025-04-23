---
layout: stdlib-reference
---

# WorldRayOrigin

## Description

Returns the origin of the current ray in world space.



## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="worldrayorigin-058.md">WorldRayOrigin</a>();

</pre>

## Return value
World-space position where the ray originated

## Remarks
Available in any-hit, closest-hit, intersection, and miss shaders


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
