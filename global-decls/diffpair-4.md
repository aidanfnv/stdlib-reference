---
layout: stdlib-reference
---

# diffPair

## Description

Constructs a <span class='code'><a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a></span> value from a primal value and a differential value.




## Signature 

<pre>
<a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="diffpair-4.md#typeparam-T" class="code_type">T</a>&gt; <a href="diffpair-4.md">diffPair</a>&lt;<a href="diffpair-4.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="diffpair-4.md#typeparam-T" class="code_type">T</a> <a href="diffpair-4.md#decl-primal" class="code_param">primal</a>,
    <a href="diffpair-4.md#typeparam-T" class="code_type">T</a>.Differential <a href="diffpair-4.md#decl-diff" class="code_param">diff</a>)
    <span class='code_keyword'>where</span> <a href="diffpair-4.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/idifferentiable-01/index.md" class="code_type">IDifferentiable</a>;

<a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="diffpair-4.md#typeparam-T" class="code_type">T</a>&gt; <a href="diffpair-4.md">diffPair</a>&lt;<a href="diffpair-4.md#typeparam-T" class="code_type">T</a>&gt;(<a href="diffpair-4.md#typeparam-T" class="code_type">T</a> <a href="diffpair-4.md#decl-primal" class="code_param">primal</a>)
    <span class='code_keyword'>where</span> <a href="diffpair-4.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/idifferentiable-01/index.md" class="code_type">IDifferentiable</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [IDifferentiable](../interfaces/idifferentiable-01/index.md)

## Parameters

####  <a id="decl-primal"></a>primal  : [T](diffpair-4.md#typeparam-T)
####  <a id="decl-diff"></a>diff  : [T](diffpair-4.md#typeparam-T)\.Differential


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
