---
layout: stdlib-reference
---

# DispatchNodeInputRecord\<T\>\.Get

## Description

Provide an access to a record object that only holds a single record.




## Signature 

<pre>
<a href="../ptr-0/index.md" class="code_type">Ptr</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt; <a href="index.md" class="code_type">DispatchNodeInputRecord</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="get-0.md">Get</a>();

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
