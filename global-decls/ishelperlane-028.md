---
layout: stdlib-reference
---

# IsHelperLane

## Description





## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="ishelperlane-028.md">IsHelperLane</a>();

</pre>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in `fragment` stage only.

#### glsl
Available in `fragment` stage only.

#### metal
Available in `fragment` stage only.

#### spirv
Available in `fragment` stage only.

Requires capability: `spvDemoteToHelperInvocationEXT`.



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
