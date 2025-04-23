---
layout: stdlib-reference
---

# interface IAtomicable

## Description

Represents types that can be used in any atomic operations.
Implemented by builtin scalar types: <span class='code'><span class="code_keyword">int</span></span>, <span class='code'><span class="code_keyword">uint</span></span>, <span class='code'>int64_t</span>, <span class='code'>uint64_t</span>, <span class='code'>int8_t</span>, <span class='code'>uint8_t</span>, <span class='code'>int16_t</span>, <span class='code'>uint16_t</span>, <span class='code'><span class="code_keyword">float</span></span>, <span class='code'><span class="code_keyword">double</span></span> and <span class='code'><span class="code_keyword">half</span></span>.



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
