---
layout: stdlib-reference
---

# T\[N\]\.dzero

## Description





## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md#typeparam-T" class="code_type">T</a>.<a href="differential-0.md" class="code_type">Differential</a>[<a href="index.md#decl-N" class="code_var">N</a>] <a href="index.md#typeparam-T" class="code_type">T</a>[<a href="index.md#decl-N" class="code_var">N</a>].<a href="dzero.md">dzero</a>()
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/idifferentiable-01/index.md" class="code_type">IDifferentiable</a>;

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
