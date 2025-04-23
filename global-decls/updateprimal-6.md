---
layout: stdlib-reference
---

# updatePrimal

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="updateprimal-6.md">updatePrimal</a>&lt;<a href="updateprimal-6.md#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">inout</span> <a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="updateprimal-6.md#typeparam-T" class="code_type">T</a>&gt; <a href="updateprimal-6.md#decl-p" class="code_param">p</a>,
    <a href="updateprimal-6.md#typeparam-T" class="code_type">T</a> <a href="updateprimal-6.md#decl-newPrimal" class="code_param">newPrimal</a>)
    <span class='code_keyword'>where</span> <a href="updateprimal-6.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/idifferentiable-01/index.md" class="code_type">IDifferentiable</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [IDifferentiable](../interfaces/idifferentiable-01/index.md)

## Parameters

####  <a id="decl-p"></a>p  : [DifferentialPair](../types/differentialpair-0c/index.md)\<[T](../types/differentialpair-0c/index.md#typeparam-T)\>
####  <a id="decl-newPrimal"></a>newPrimal  : [T](updateprimal-6.md#typeparam-T)


<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
