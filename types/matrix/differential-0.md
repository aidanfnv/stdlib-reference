---
layout: stdlib-reference
---

# typealias matrix\<T,N,M\>\.Differential

## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>, <a href="index.md#decl-M" class="code_var">M</a>&gt;.<a href="differential-0.md" class="code_type">Differential</a> = 
    <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>, <a href="index.md#decl-M" class="code_var">M</a>&gt;;
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
