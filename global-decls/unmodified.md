---
layout: stdlib-reference
---

# unmodified

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="unmodified.md">unmodified</a>&lt;<a href="unmodified.md#typeparam-T" class="code_type">T</a>&gt;(<span class="code_keyword">out</span> <a href="unmodified.md#typeparam-T" class="code_type">T</a> <a href="unmodified.md#decl-SLANG_anonymous_6" class="code_param">SLANG_anonymous_6</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T

## Parameters

####  <a id="decl-SLANG_anonymous_6"></a>SLANG\_anonymous\_6  : [T](unmodified.md#typeparam-T)


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
