---
layout: stdlib-reference
---

# matrix\<T,R,C\>\.dzero

## Description





## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>, <a href="index.md#decl-M" class="code_var">M</a>&gt; <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="dzero.md">dzero</a>()
    <span class='code_keyword'>where</span> <a href="t-0.md" class="code_type">T</a> : <a href="../../interfaces/idifferentiable-01/index.md" class="code_type">IDifferentiable</a>;

</pre>


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
