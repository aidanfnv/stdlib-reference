---
layout: stdlib-reference
---

# typealias RasterizerOrderedBuffer\<T, format:int\>

## Description



## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="rasterizerorderedbuffer-0ah.md" class="code_type">RasterizerOrderedBuffer</a>&lt;T, format:<span class="code_keyword">int</span>&gt; = 
    <a href="0texture-01/index.md" class="code_type">_Texture</a>&lt;T, <a href="0_shapebuffer-027/index.md" class="code_type">__ShapeBuffer</a>, 0, 0, 0, 2, 0, 0, format&gt;;
</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [ITexelElement](../interfaces/itexelelement-016/index.md)
####  <a id="decl-format"></a>format  : int = 0


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
