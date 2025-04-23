---
layout: stdlib-reference
---

# WorkgroupSize

## Description





## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, 3&gt; <a href="workgroupsize-09.md">WorkgroupSize</a>();

</pre>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in `compute` stage only.

#### glsl
Available in `compute` stage only.

#### c
Available in `compute` stage only.

#### cpp
Available in `compute` stage only.

#### cuda
Available in `compute` stage only.

#### metal
Available in `compute` stage only.

#### spirv
Available in `compute` stage only.

#### wgsl
Available in `compute` stage only.




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
