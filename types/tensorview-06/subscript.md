---
layout: stdlib-reference
---

# TensorView\<T\>\.subscript

## Description





## Signature 

<pre>
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="subscript.md">subscript</a>(<span class="code_keyword">uint</span> <a href="subscript.md#decl-index" class="code_param">index</a>);

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="subscript.md">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i1" class="code_param">i1</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i2" class="code_param">i2</a>);

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="subscript.md">subscript</a>(<a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 2&gt; <a href="subscript.md#decl-i" class="code_param">i</a>);

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="subscript.md">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i1" class="code_param">i1</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i2" class="code_param">i2</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i3" class="code_param">i3</a>);

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="subscript.md">subscript</a>(<a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 3&gt; <a href="subscript.md#decl-i" class="code_param">i</a>);

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="subscript.md">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i1" class="code_param">i1</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i2" class="code_param">i2</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i3" class="code_param">i3</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i4" class="code_param">i4</a>);

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="subscript.md">subscript</a>(<a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="subscript.md#decl-i" class="code_param">i</a>);

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="subscript.md">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i1" class="code_param">i1</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i2" class="code_param">i2</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i3" class="code_param">i3</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i4" class="code_param">i4</a>,
    <span class="code_keyword">uint</span> <a href="subscript.md#decl-i5" class="code_param">i5</a>);

</pre>

## Parameters

####  <a id="decl-index"></a>index  : uint
####  <a id="decl-i1"></a>i1  : uint
####  <a id="decl-i2"></a>i2  : uint
####  <a id="decl-i"></a>i  : [vector](../vector/index.md)\<uint, 2\>
####  <a id="decl-i3"></a>i3  : uint
####  <a id="decl-i"></a>i  : [vector](../vector/index.md)\<uint, 3\>
####  <a id="decl-i4"></a>i4  : uint
####  <a id="decl-i"></a>i  : [vector](../vector/index.md)\<uint, 4\>
####  <a id="decl-i5"></a>i5  : uint


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
