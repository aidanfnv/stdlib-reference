---
layout: stdlib-reference
---

# typealias Sampler1DArrayShadow\<format:int\>

## Description

Represents a handle to a 1D combined texture-sampler for shadow comparison.

## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="sampler1darrayshadow-089e.md" class="code_type">Sampler1DArrayShadow</a>&lt;format:<span class="code_keyword">int</span>&gt; = 
    <a href="0texture-01/index.md" class="code_type">_Texture</a>&lt;<span class="code_keyword">float</span>, <a href="0_shape1d-028/index.md" class="code_type">__Shape1D</a>, 1, 0, 0, 0, 1, 1, format&gt;;
</pre>

## Generic Parameters

####  <a id="decl-format"></a>format  : int = 0
The storage format of the texture.


## See also

Please refer to <span class='code'><a href="0texture-01/index.md" class="code_type">_Texture</a></span> for more information about texture types.



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
