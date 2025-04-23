---
layout: stdlib-reference
---

# updatePair

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="updatepair-6.md">updatePair</a>&lt;<a href="updatepair-6.md#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">inout</span> <a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="updatepair-6.md#typeparam-T" class="code_type">T</a>&gt; <a href="updatepair-6.md#decl-p" class="code_param">p</a>,
    <a href="updatepair-6.md#typeparam-T" class="code_type">T</a> <a href="updatepair-6.md#decl-newPrimal" class="code_param">newPrimal</a>,
    <a href="updatepair-6.md#typeparam-T" class="code_type">T</a>.Differential <a href="updatepair-6.md#decl-newDiff" class="code_param">newDiff</a>)
    <span class='code_keyword'>where</span> <a href="updatepair-6.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/idifferentiable-01/index.md" class="code_type">IDifferentiable</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [IDifferentiable](../interfaces/idifferentiable-01/index.md)

## Parameters

####  <a id="decl-p"></a>p  : [DifferentialPair](../types/differentialpair-0c/index.md)\<[T](../types/differentialpair-0c/index.md#typeparam-T)\>
####  <a id="decl-newPrimal"></a>newPrimal  : [T](updatepair-6.md#typeparam-T)
####  <a id="decl-newDiff"></a>newDiff  : [T](updatepair-6.md#typeparam-T)\.Differential


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
