---
layout: stdlib-reference
---

# CoopMat\<T, S:CoopMatScope, M:int, N:int, R:CoopMatMatrixUse\>\.init

## Description





## Signature 

<pre>
<a href="index.md" class="code_type">CoopMat</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-S" class="code_var">S</a>:<a href="../coopmatscope-047/index.md" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../coopmatmatrixuse-047d/index.md" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="init.md">init</a>()
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="index.md" class="code_type">CoopMat</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-S" class="code_var">S</a>:<a href="../coopmatscope-047/index.md" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../coopmatmatrixuse-047d/index.md" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="init.md">init</a>(
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="init.md#decl-t" class="code_param">t</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="index.md" class="code_type">CoopMat</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-S" class="code_var">S</a>:<a href="../coopmatscope-047/index.md" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../coopmatmatrixuse-047d/index.md" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="init.md">init</a>&lt;<a href="init.md#typeparam-U" class="code_type">U</a>&gt;(
    <a href="index.md" class="code_type">CoopMat</a>&lt;<a href="init.md#typeparam-U" class="code_type">U</a>, <a href="index.md#decl-S" class="code_var">S</a>, <a href="index.md#decl-M" class="code_var">M</a>, <a href="index.md#decl-N" class="code_var">N</a>, <a href="index.md#decl-R" class="code_var">R</a>&gt; <a href="init.md#decl-other" class="code_param">other</a>)
    <span class='code_keyword'>where</span> <a href="init.md#typeparam-U" class="code_type">U</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="index.md" class="code_type">CoopMat</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-S" class="code_var">S</a>:<a href="../coopmatscope-047/index.md" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../coopmatmatrixuse-047d/index.md" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="init.md">init</a>(
    <a href="index.md" class="code_type">CoopMat</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-S" class="code_var">S</a>, <a href="index.md#decl-M" class="code_var">M</a>, <a href="index.md#decl-N" class="code_var">N</a>, <a href="index.md#decl-R" class="code_var">R</a>&gt; <a href="init.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="index.md" class="code_type">CoopMat</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-S" class="code_var">S</a>:<a href="../coopmatscope-047/index.md" class="code_type">CoopMatScope</a>, M:<span class="code_keyword">int</span>, N:<span class="code_keyword">int</span>, R:<a href="../coopmatmatrixuse-047d/index.md" class="code_type">CoopMatMatrixUse</a>&gt;.<a href="init.md">init</a>(
    <span class="code_keyword">int</span> <a href="init.md#decl-i" class="code_param">i</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../../interfaces/0_builtinarithmetictype-029j/index.md)

## Parameters

####  <a id="decl-t"></a>t  : [T](index.md#typeparam-T)
####  <a id="decl-other"></a>other  : [CoopMat](index.md)\<U, [S](index.md#decl-S), [M](index.md#decl-M), [N](index.md#decl-N), [R](index.md#decl-R)\>
####  <a id="decl-x"></a>x  : [CoopMat](index.md)\<[T](index.md#typeparam-T), [S](index.md#decl-S), [M](index.md#decl-M), [N](index.md#decl-N), [R](index.md#decl-R)\>
####  <a id="decl-i"></a>i  : int

## Availability and Requirements

Defined for the following targets:

#### spirv
Available in all stages.

Requires capability: `spvCooperativeMatrixKHR`.



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
