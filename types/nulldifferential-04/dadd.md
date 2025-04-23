---
layout: stdlib-reference
---

# NullDifferential\.dadd

## Description





## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">NullDifferential</a> <a href="index.md" class="code_type">NullDifferential</a>.<a href="dadd.md">dadd</a>(
    <a href="index.md" class="code_type">NullDifferential</a> <a href="dadd.md#decl-SLANG_anonymous_7" class="code_param">SLANG_anonymous_7</a>,
    <a href="index.md" class="code_type">NullDifferential</a> <a href="dadd.md#decl-SLANG_anonymous_8" class="code_param">SLANG_anonymous_8</a>);

</pre>

## Parameters

####  <a id="decl-SLANG_anonymous_7"></a>SLANG\_anonymous\_7  : [NullDifferential](index.md)
####  <a id="decl-SLANG_anonymous_8"></a>SLANG\_anonymous\_8  : [NullDifferential](index.md)


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
