---
layout: stdlib-reference
---

# IRangedValue.minValue

## Description

The minimum value that an instance of the type can hold.
This is a constant value specific to the type.


## Signature
<pre>
<span class='code_keyword'>static</span> <span class='code_keyword'>const</span> <a href="index.md" class="code_type">IRangedValue</a>.<span class="code_keyword">This</span> <a href="index.md" class="code_type">IRangedValue</a>.<a href="minvalue-3.md" class="code_var">minValue</a>;
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
