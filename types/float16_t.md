---
layout: stdlib-reference
---

# typealias float16\_t

## Description



## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="float16_t.md" class="code_type">float16_t</a> = <span class="code_keyword">half</span>;
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
