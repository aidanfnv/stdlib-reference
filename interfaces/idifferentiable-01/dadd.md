---
layout: stdlib-reference
---

# IDifferentiable\.dadd

## Description

Adds two differential values and returns the result.




## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">IDifferentiable</a>.<span class="code_keyword">This</span>.Differential <a href="index.md" class="code_type">IDifferentiable</a>.<a href="dadd.md">dadd</a>(
    <a href="index.md" class="code_type">IDifferentiable</a>.<span class="code_keyword">This</span>.Differential <a href="dadd.md#decl-SLANG_anonymous_0" class="code_param">SLANG_anonymous_0</a>,
    <a href="index.md" class="code_type">IDifferentiable</a>.<span class="code_keyword">This</span>.Differential <a href="dadd.md#decl-SLANG_anonymous_1" class="code_param">SLANG_anonymous_1</a>);

</pre>

## Parameters

####  <a id="decl-SLANG_anonymous_0"></a>SLANG\_anonymous\_0  : [IDifferentiable](index.md)\.This\.Differential
####  <a id="decl-SLANG_anonymous_1"></a>SLANG\_anonymous\_1  : [IDifferentiable](index.md)\.This\.Differential
Adds two differential values and returns the result.



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
