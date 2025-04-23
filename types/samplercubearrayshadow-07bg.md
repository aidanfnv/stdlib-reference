---
layout: stdlib-reference
---

# typealias SamplerCubeArrayShadow\<format:int\>

## Description

Represents a handle to a Cube combined texture-sampler for shadow comparison.

## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="samplercubearrayshadow-07bg.md" class="code_type">SamplerCubeArrayShadow</a>&lt;format:<span class="code_keyword">int</span>&gt; = 
    <a href="0texture-01/index.md" class="code_type">_Texture</a>&lt;<span class="code_keyword">float</span>, <a href="0_shapecube-027/index.md" class="code_type">__ShapeCube</a>, 1, 0, 0, 0, 1, 1, format&gt;;
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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
