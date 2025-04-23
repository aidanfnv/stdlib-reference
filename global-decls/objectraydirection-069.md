---
layout: stdlib-reference
---

# ObjectRayDirection

## Description

Returns the ray direction in object space of the current instance.



## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="objectraydirection-069.md">ObjectRayDirection</a>();

</pre>

## Return value
Object-space direction vector of the ray

## Remarks
Transformed by the inverse of the instance transform


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `intersection`, `closesthit`, `anyhit`.

#### glsl
Available in stages: `intersection`, `closesthit`, `anyhit`.

#### cuda
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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
