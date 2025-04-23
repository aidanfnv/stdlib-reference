---
layout: stdlib-reference
---

# attribute [Flags]

## Description

Marks a enum type as a bit flag enum. Bit flag enums will have their enum cases assigned to powers of 2 instead of consecutive integers.


## Signature

<pre>
[<a href="flags-0.md">Flags</a>]
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
