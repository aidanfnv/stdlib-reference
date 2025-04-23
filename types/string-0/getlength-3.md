---
layout: stdlib-reference
---

# String\.getLength

## Description

Returns the length of the string.




## Signature 

<pre>
int64_t <a href="index.md" class="code_type">String</a>.<a href="getlength-3.md">getLength</a>();

</pre>

## Availability and Requirements

Defined for the following targets:

#### cpp
Available in all stages.




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
