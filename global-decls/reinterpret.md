---
layout: stdlib-reference
---

# reinterpret

## Description

Reinterpret type <span class='code'><a href="reinterpret.md#typeparam-U" class="code_type">U</a></span> as type <span class='code'><a href="reinterpret.md#typeparam-T" class="code_type">T</a></span>. <span class='code'><a href="reinterpret.md#typeparam-T" class="code_type">T</a></span> and <span class='code'><a href="reinterpret.md#typeparam-U" class="code_type">U</a></span>
can be any scalar, vector, matrix, struct or array types.




## Signature 

<pre>
<a href="reinterpret.md#typeparam-T" class="code_type">T</a> <a href="reinterpret.md">reinterpret</a>&lt;<a href="reinterpret.md#typeparam-T" class="code_type">T</a>, <a href="reinterpret.md#typeparam-U" class="code_type">U</a>&gt;(<a href="reinterpret.md#typeparam-U" class="code_type">U</a> <a href="reinterpret.md#decl-value" class="code_param">value</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T
####  <a id="typeparam-U"></a>U

## Parameters

####  <a id="decl-value"></a>value  : [U](reinterpret.md#typeparam-U)


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
