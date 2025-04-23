---
layout: stdlib-reference
---

# T\[N\]\.dadd

## Description





## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md#typeparam-T" class="code_type">T</a>.<a href="differential-0.md" class="code_type">Differential</a>[<a href="index.md#decl-N" class="code_var">N</a>] <a href="index.md#typeparam-T" class="code_type">T</a>[<a href="index.md#decl-N" class="code_var">N</a>].<a href="dadd.md">dadd</a>(
    <a href="index.md#typeparam-T" class="code_type">T</a>.<a href="differential-0.md" class="code_type">Differential</a>[<a href="index.md#decl-N" class="code_var">N</a>] <a href="dadd.md#decl-a" class="code_param">a</a>,
    <a href="index.md#typeparam-T" class="code_type">T</a>.<a href="differential-0.md" class="code_type">Differential</a>[<a href="index.md#decl-N" class="code_var">N</a>] <a href="dadd.md#decl-b" class="code_param">b</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/idifferentiable-01/index.md" class="code_type">IDifferentiable</a>;

</pre>

## Parameters

####  <a id="decl-a"></a>a  : [T](index.md#typeparam-T)\.[Differential](differential-0.md) \[ [N](index.md#decl-N) \]
####  <a id="decl-b"></a>b  : [T](index.md#typeparam-T)\.[Differential](differential-0.md) \[ [N](index.md#decl-N) \]


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
