---
layout: stdlib-reference
---

# Atomic\<T\>\.exchange

## Description

Atomically replace the stored <span class='code'><a href="index.md#typeparam-T" class="code_type">T</a></span> value with a new <span class='code'><a href="index.md#typeparam-T" class="code_type">T</a></span> value and return
replaced value




## Signature 

<pre>
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">Atomic</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="exchange.md">exchange</a>(
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="exchange.md#decl-newValue" class="code_param">newValue</a>,
    <a href="../memoryorder-06/index.md" class="code_type">MemoryOrder</a> <a href="exchange.md#decl-order" class="code_param">order</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/iatomicable-01/index.md" class="code_type">IAtomicable</a>;

</pre>

## Parameters

####  <a id="decl-newValue"></a>newValue  : [T](index.md#typeparam-T)
####  <a id="decl-order"></a>order  : [MemoryOrder](../memoryorder-06/index.md) = [MemoryOrder](../memoryorder-06/index.md)\.[Relaxed](../memoryorder-06/index.md#decl-Relaxed)


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
