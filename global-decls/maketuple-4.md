---
layout: stdlib-reference
---

# makeTuple

## Description

Construct a tuple from several values in order




## Signature 

<pre>
<a href="../types/tuple-0/index.md" class="code_type">Tuple</a>&lt;<a href="maketuple-4.md#typeparam-T" class="code_type">T</a>&gt; <a href="maketuple-4.md">makeTuple</a>&lt;<span class="code_keyword">each</span> <a href="maketuple-4.md#typeparam-T" class="code_type">T</a>&gt;(<a href="maketuple-4.md#typeparam-T" class="code_type">T</a> <a href="maketuple-4.md#decl-v" class="code_param">v</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T

## Parameters

####  <a id="decl-v"></a>v  : [T](maketuple-4.md#typeparam-T)


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
