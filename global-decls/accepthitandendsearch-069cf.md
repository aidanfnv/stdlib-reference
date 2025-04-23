---
layout: stdlib-reference
---

# AcceptHitAndEndSearch

## Description

Accepts the current intersection and terminates further traversal.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="accepthitandendsearch-069cf.md">AcceptHitAndEndSearch</a>();

</pre>

## Remarks
Used in any-hit shaders to immediately accept an intersection


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
      const href = link.getAttribute('href');
      if (href && href.includes('.md')) {
        // This regex will handle .md links with or without fragment identifiers or query parameters
        link.href = link.href.replace(/(.+)\.md(#[^?]*)?(\?.*)?$/, '$1.html$2$3');
      }
    });
  });
}
</script>
