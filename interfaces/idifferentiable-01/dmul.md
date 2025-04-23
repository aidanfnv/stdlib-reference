---
layout: stdlib-reference
---

# IDifferentiable\.dmul

## Description

Multiplies a scalar value of a built-in real type with a differential value and returns the result.




## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">IDifferentiable</a>.<span class="code_keyword">This</span>.Differential <a href="index.md" class="code_type">IDifferentiable</a>.<a href="dmul.md">dmul</a>&lt;<a href="dmul.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="dmul.md#typeparam-T" class="code_type">T</a> <a href="dmul.md#decl-SLANG_anonymous_2" class="code_param">SLANG_anonymous_2</a>,
    <a href="index.md" class="code_type">IDifferentiable</a>.<span class="code_keyword">This</span>.Differential <a href="dmul.md#decl-SLANG_anonymous_3" class="code_param">SLANG_anonymous_3</a>)
    <span class='code_keyword'>where</span> <a href="dmul.md#typeparam-T" class="code_type">T</a> : __BuiltinRealType;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: \_\_BuiltinRealType

## Parameters

####  <a id="decl-SLANG_anonymous_2"></a>SLANG\_anonymous\_2  : [T](dmul.md#typeparam-T)
####  <a id="decl-SLANG_anonymous_3"></a>SLANG\_anonymous\_3  : [IDifferentiable](index.md)\.This\.Differential
Multiplies a scalar value of a built-in real type with a differential value and returns the result.



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
