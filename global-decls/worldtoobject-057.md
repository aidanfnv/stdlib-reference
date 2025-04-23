---
layout: stdlib-reference
---

# WorldToObject

## Description

Alias for WorldToObject3x4.




## Signature 

<pre>
<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<span class="code_keyword">float</span>, 3, 4&gt; <a href="worldtoobject-057.md">WorldToObject</a>();

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
