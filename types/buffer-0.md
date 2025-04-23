---
layout: stdlib-reference
---

# typealias Buffer\<T, format:int\>

## Description



## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="buffer-0.md" class="code_type">Buffer</a>&lt;T, format:<span class="code_keyword">int</span>&gt; = <a href="buffer-0.md" class="code_type">Buffer</a>&lt;T&gt;;
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
