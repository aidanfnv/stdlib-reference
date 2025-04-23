---
layout: stdlib-reference
---

# typealias Tuple\<T\>\.Differential

## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="index.md" class="code_type">Tuple</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="differential-0.md" class="code_type">Differential</a> = <a href="index.md" class="code_type">Tuple</a>&lt;<span class="code_keyword">expand</span> <span class="code_keyword">each</span> <a href="index.md#typeparam-T" class="code_type">T</a>.<a href="differential-0.md" class="code_type">Differential</a>&gt;;
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
