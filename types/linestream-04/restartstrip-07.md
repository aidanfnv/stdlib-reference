---
layout: stdlib-reference
---

# LineStream\<T\>\.RestartStrip

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">LineStream</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="restartstrip-07.md">RestartStrip</a>();

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
