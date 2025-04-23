---
layout: stdlib-reference
---

# DiffTensorView\<T, A\>\.subscript

## Description





## Signature 

<pre>
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">DiffTensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript.md">subscript</a>(<span class="code_keyword">uint</span> <a href="subscript.md#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-A" class="code_type">A</a> : <a href="../../interfaces/idifftensorwrapper-015b/index.md" class="code_type">IDiffTensorWrapper</a>;

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">DiffTensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript.md">subscript</a>(<a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 2&gt; <a href="subscript.md#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-A" class="code_type">A</a> : <a href="../../interfaces/idifftensorwrapper-015b/index.md" class="code_type">IDiffTensorWrapper</a>;

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">DiffTensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript.md">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-A" class="code_type">A</a> : <a href="../../interfaces/idifftensorwrapper-015b/index.md" class="code_type">IDiffTensorWrapper</a>;

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">DiffTensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript.md">subscript</a>(<a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 3&gt; <a href="subscript.md#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-A" class="code_type">A</a> : <a href="../../interfaces/idifftensorwrapper-015b/index.md" class="code_type">IDiffTensorWrapper</a>;

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">DiffTensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript.md">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-y" class="code_param">y</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-z" class="code_param">z</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-A" class="code_type">A</a> : <a href="../../interfaces/idifftensorwrapper-015b/index.md" class="code_type">IDiffTensorWrapper</a>;

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">DiffTensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript.md">subscript</a>(<a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="subscript.md#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-A" class="code_type">A</a> : <a href="../../interfaces/idifftensorwrapper-015b/index.md" class="code_type">IDiffTensorWrapper</a>;

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">DiffTensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript.md">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-y" class="code_param">y</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-z" class="code_param">z</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-w" class="code_param">w</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-A" class="code_type">A</a> : <a href="../../interfaces/idifftensorwrapper-015b/index.md" class="code_type">IDiffTensorWrapper</a>;

</pre>

## Parameters

####  <a id="decl-index"></a>index  : uint
####  <a id="decl-index"></a>index  : [vector](../vector/index.md)\<uint, 2\>
####  <a id="decl-x"></a>x  : uint
####  <a id="decl-y"></a>y  : uint
####  <a id="decl-index"></a>index  : [vector](../vector/index.md)\<uint, 3\>
####  <a id="decl-z"></a>z  : uint
####  <a id="decl-index"></a>index  : [vector](../vector/index.md)\<uint, 4\>
####  <a id="decl-w"></a>w  : uint


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
