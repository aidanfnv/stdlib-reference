---
layout: stdlib-reference
---

# typealias \_Texture\<T, Shape, 0, 0, sampleCount, 0, isShadow, 0, format\>\.Footprint

## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, 0, 0, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, 0, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, 0, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="footprint-0.md" class="code_type">Footprint</a> = 
    <a href="../texturefootprint-07/index.md" class="code_type">TextureFootprint</a>&lt;<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt;;
</pre>


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
