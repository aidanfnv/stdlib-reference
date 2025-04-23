---
layout: stdlib-reference
---

# Tuple\<T\>\.dadd

## Description





## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">Tuple</a>&lt;<span class="code_keyword">expand</span> <span class="code_keyword">each</span> <a href="index.md#typeparam-T" class="code_type">T</a>.<a href="differential-0.md" class="code_type">Differential</a>&gt; <a href="index.md" class="code_type">Tuple</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="dadd.md">dadd</a>(
    <a href="index.md" class="code_type">Tuple</a>&lt;<span class="code_keyword">expand</span> <span class="code_keyword">each</span> <a href="index.md#typeparam-T" class="code_type">T</a>.<a href="differential-0.md" class="code_type">Differential</a>&gt; <a href="dadd.md#decl-a" class="code_param">a</a>,
    <a href="index.md" class="code_type">Tuple</a>&lt;<span class="code_keyword">expand</span> <span class="code_keyword">each</span> <a href="index.md#typeparam-T" class="code_type">T</a>.<a href="differential-0.md" class="code_type">Differential</a>&gt; <a href="dadd.md#decl-b" class="code_param">b</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/idifferentiable-01/index.md" class="code_type">IDifferentiable</a>;

</pre>

## Parameters

####  <a id="decl-a"></a>a  : [Tuple](index.md)\<expand each [T](index.md#typeparam-T)\.[Differential](differential-0.md)\>
####  <a id="decl-b"></a>b  : [Tuple](index.md)\<expand each [T](index.md#typeparam-T)\.[Differential](differential-0.md)\>


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
