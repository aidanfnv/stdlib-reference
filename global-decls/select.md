---
layout: stdlib-reference
---

# select

## Description





## Signature 

<pre>
<a href="select.md#typeparam-T" class="code_type">T</a> <a href="select.md">select</a>&lt;<a href="select.md#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">bool</span> <a href="select.md#decl-condition" class="code_param">condition</a>,
    <a href="select.md#typeparam-T" class="code_type">T</a> <a href="select.md#decl-ifTrue" class="code_param">ifTrue</a>,
    <a href="select.md#typeparam-T" class="code_type">T</a> <a href="select.md#decl-ifFalse" class="code_param">ifFalse</a>);

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="select.md#typeparam-T" class="code_type">T</a>, <a href="select.md#decl-N" class="code_var">N</a>&gt; <a href="select.md">select</a>&lt;<a href="select.md#typeparam-T" class="code_type">T</a>, <a href="select.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">bool</span>, <a href="select.md#decl-N" class="code_var">N</a>&gt; <a href="select.md#decl-condition" class="code_param">condition</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="select.md#typeparam-T" class="code_type">T</a>, <a href="select.md#decl-N" class="code_var">N</a>&gt; <a href="select.md#decl-ifTrue" class="code_param">ifTrue</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="select.md#typeparam-T" class="code_type">T</a>, <a href="select.md#decl-N" class="code_var">N</a>&gt; <a href="select.md#decl-ifFalse" class="code_param">ifFalse</a>);

<a href="../types/optional-0/index.md" class="code_type">Optional</a>&lt;<a href="select.md#typeparam-T" class="code_type">T</a>&gt; <a href="select.md">select</a>&lt;<a href="select.md#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">bool</span> <a href="select.md#decl-condition" class="code_param">condition</a>,
    __none_t <a href="select.md#decl-ifTrue" class="code_param">ifTrue</a>,
    <a href="select.md#typeparam-T" class="code_type">T</a> <a href="select.md#decl-ifFalse" class="code_param">ifFalse</a>);

<a href="../types/optional-0/index.md" class="code_type">Optional</a>&lt;<a href="select.md#typeparam-T" class="code_type">T</a>&gt; <a href="select.md">select</a>&lt;<a href="select.md#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">bool</span> <a href="select.md#decl-condition" class="code_param">condition</a>,
    <a href="select.md#typeparam-T" class="code_type">T</a> <a href="select.md#decl-ifTrue" class="code_param">ifTrue</a>,
    __none_t <a href="select.md#decl-ifFalse" class="code_param">ifFalse</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-condition"></a>condition  : bool
####  <a id="decl-ifTrue"></a>ifTrue  : [T](select.md#typeparam-T)
####  <a id="decl-ifFalse"></a>ifFalse  : [T](select.md#typeparam-T)
####  <a id="decl-condition"></a>condition  : [vector](../types/vector/index.md)\<bool, [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-ifTrue"></a>ifTrue  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-ifFalse"></a>ifFalse  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-ifTrue"></a>ifTrue  : \_\_none\_t
####  <a id="decl-ifFalse"></a>ifFalse  : \_\_none\_t


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
