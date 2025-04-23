---
layout: stdlib-reference
---

# typealias DifferentialPtrPair\<T\>\.DifferentialElementType

## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="index.md" class="code_type">DifferentialPtrPair</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="differentialelementtype-0cj.md" class="code_type">DifferentialElementType</a> = 
    <a href="index.md#typeparam-T" class="code_type">T</a>.<a href="differential-0.md" class="code_type">Differential</a>;
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
