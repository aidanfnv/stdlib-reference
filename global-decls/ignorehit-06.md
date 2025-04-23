---
layout: stdlib-reference
---

# IgnoreHit

## Description

Ignores the current intersection and continues traversal.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="ignorehit-06.md">IgnoreHit</a>();

</pre>

## Remarks
Used in any-hit shaders to reject potential intersections


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in `anyhit` stage only.

#### glsl
Available in `anyhit` stage only.

#### cuda
Available in `anyhit` stage only.

#### spirv
Available in `anyhit` stage only.

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
