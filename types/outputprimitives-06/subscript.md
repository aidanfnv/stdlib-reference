---
layout: stdlib-reference
---

# OutputPrimitives\<T, MAX\_PRIMITIVES:uint\>\.subscript

## Description





## Signature 

<pre>
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">OutputPrimitives</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-MAX_PRIMITIVES" class="code_var">MAX_PRIMITIVES</a>:<span class="code_keyword">uint</span>&gt;.<a href="subscript.md">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-index" class="code_param">index</a>);

</pre>

## Parameters

####  <a id="decl-index"></a>index  : uint


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
