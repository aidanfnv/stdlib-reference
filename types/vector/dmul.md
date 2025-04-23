---
layout: stdlib-reference
---

# vector\<T,N\>\.dmul

## Description





## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="index.md" class="code_type">vector</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>&gt; <a href="index.md" class="code_type">vector</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>&gt;.<a href="dmul.md">dmul</a>&lt;<a href="dmul.md#typeparam-U" class="code_type">U</a>&gt;(
    <a href="dmul.md#typeparam-U" class="code_type">U</a> <a href="dmul.md#decl-a" class="code_param">a</a>,
    <a href="index.md" class="code_type">vector</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>&gt; <a href="dmul.md#decl-b" class="code_param">b</a>)
    <span class='code_keyword'>where</span> <a href="dmul.md#typeparam-U" class="code_type">U</a> : __BuiltinRealType
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/idifferentiable-01/index.md" class="code_type">IDifferentiable</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U: \_\_BuiltinRealType

## Parameters

####  <a id="decl-a"></a>a  : [U](dmul.md#typeparam-U)
####  <a id="decl-b"></a>b  : [vector](index.md)\<[T](index.md#typeparam-T), [N](index.md#decl-N)\>


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
