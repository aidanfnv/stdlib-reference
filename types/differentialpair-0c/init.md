---
layout: stdlib-reference
---

# DifferentialPair\<T\>\.init

## Description





## Signature 

<pre>
<a href="index.md" class="code_type">DifferentialPair</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="init.md">init</a>(
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="init.md#decl-_primal" class="code_param">_primal</a>,
    <a href="index.md#typeparam-T" class="code_type">T</a>.<a href="differential-0.md" class="code_type">Differential</a> <a href="init.md#decl-_differential" class="code_param">_differential</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/idifferentiable-01/index.md" class="code_type">IDifferentiable</a>;

</pre>

## Parameters

####  <a id="decl-_primal"></a>\_primal  : [T](index.md#typeparam-T)
####  <a id="decl-_differential"></a>\_differential  : [T](index.md#typeparam-T)\.[Differential](differential-0.md)


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
