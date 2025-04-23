---
layout: stdlib-reference
---

# CoopMat\<T, S:CoopMatScope, M:int, N:int, R:CoopMatMatrixUse\>\.equals

## Description





## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="index.md" class="code_type">CoopMat</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-S" class="code_var">S</a>:<a href="../coopmatscope-047/index.md" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../coopmatmatrixuse-047d/index.md" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="equals.md">equals</a>(
    <a href="index.md" class="code_type">CoopMat</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-S" class="code_var">S</a>, <a href="index.md#decl-M" class="code_var">M</a>, <a href="index.md#decl-N" class="code_var">N</a>, <a href="index.md#decl-R" class="code_var">R</a>&gt; <a href="equals.md#decl-other" class="code_param">other</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Parameters

####  <a id="decl-other"></a>other  : [CoopMat](index.md)\<[T](index.md#typeparam-T), [S](index.md#decl-S), [M](index.md#decl-M), [N](index.md#decl-N), [R](index.md#decl-R)\>


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
