---
layout: stdlib-reference
---

# DifferentialPair\<T\>\.dadd

## Description





## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">DifferentialPair</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>.<a href="differential-0.md" class="code_type">Differential</a>&gt; <a href="index.md" class="code_type">DifferentialPair</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="dadd.md">dadd</a>(
    <a href="index.md" class="code_type">DifferentialPair</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>.<a href="differential-0.md" class="code_type">Differential</a>&gt; <a href="dadd.md#decl-a" class="code_param">a</a>,
    <a href="index.md" class="code_type">DifferentialPair</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>.<a href="differential-0.md" class="code_type">Differential</a>&gt; <a href="dadd.md#decl-b" class="code_param">b</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/idifferentiable-01/index.md" class="code_type">IDifferentiable</a>;

</pre>

## Parameters

####  <a id="decl-a"></a>a  : [DifferentialPair](index.md)\<[T](index.md#typeparam-T)\.[Differential](differential-0.md)\>
####  <a id="decl-b"></a>b  : [DifferentialPair](index.md)\<[T](index.md#typeparam-T)\.[Differential](differential-0.md)\>


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
