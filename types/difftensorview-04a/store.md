---
layout: stdlib-reference
---

# DiffTensorView\<T, A\>\.store

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">DiffTensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-A" class="code_type">A</a>&gt;.<a href="store.md">store</a>(
    <span class="code_keyword">uint</span> <a href="store.md#decl-x" class="code_param">x</a>,
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="store.md#decl-val" class="code_param">val</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-A" class="code_type">A</a> : <a href="../../interfaces/idifftensorwrapper-015b/index.md" class="code_type">IDiffTensorWrapper</a>;

<span class="code_keyword">void</span> <a href="index.md" class="code_type">DiffTensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-A" class="code_type">A</a>&gt;.<a href="store.md">store</a>&lt;<a href="store.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="store.md#decl-N" class="code_var">N</a>&gt; <a href="store.md#decl-x" class="code_param">x</a>,
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="store.md#decl-val" class="code_param">val</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-A" class="code_type">A</a> : <a href="../../interfaces/idifftensorwrapper-015b/index.md" class="code_type">IDiffTensorWrapper</a>;

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-x"></a>x  : uint
####  <a id="decl-val"></a>val  : [T](index.md#typeparam-T)
####  <a id="decl-x"></a>x  : [vector](../vector/index.md)\<uint, [N](../vector/index.md#decl-N)\>


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
