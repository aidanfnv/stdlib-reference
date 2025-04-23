---
layout: stdlib-reference
---

# IInteger\.toUInt64

## Description

Converts the value of the current instance to an <span class='code'>uint64_t</span>.



## Signature 

<pre>
uint64_t <a href="index.md" class="code_type">IInteger</a>.<a href="touint64-23.md">toUInt64</a>();

</pre>

## Return value
The converted <span class='code'>uint64_t</span> value.



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
