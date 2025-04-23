---
layout: stdlib-reference
---

# \_\_BuiltinFloatingPointType\.getPi

## Description

Get the value of the mathematical constant pi in this type.




## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">__BuiltinFloatingPointType</a>.<span class="code_keyword">This</span> <a href="index.md" class="code_type">__BuiltinFloatingPointType</a>.<a href="getpi-3.md">getPi</a>();

</pre>


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
