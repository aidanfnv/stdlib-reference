---
layout: stdlib-reference
---

# typealias RWBuffer\<T, format:int\>

## Description



## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="rwbuffer-012.md" class="code_type">RWBuffer</a>&lt;T, format:<span class="code_keyword">int</span>&gt; = <a href="rwbuffer-012.md" class="code_type">RWBuffer</a>&lt;T&gt;;
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
