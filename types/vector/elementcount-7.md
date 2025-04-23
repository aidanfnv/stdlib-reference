---
layout: stdlib-reference
---

# vector<half,N>.elementCount

## Signature
<pre>
<span class='code_keyword'>static</span> <span class='code_keyword'>const</span> <span class="code_keyword">int</span> <a href="index.md" class="code_type">vector</a>&lt;<span class="code_keyword">half</span>, <a href="index.md#decl-N" class="code_var">N</a>&gt;.<a href="elementcount-7.md" class="code_var">elementCount</a> = N;
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
