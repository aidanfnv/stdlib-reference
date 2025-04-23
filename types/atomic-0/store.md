---
layout: stdlib-reference
---

# Atomic\<T\>\.store

## Description

Atomically store a new <span class='code'><a href="index.md#typeparam-T" class="code_type">T</a></span> value




## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">Atomic</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="store.md">store</a>(
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="store.md#decl-newValue" class="code_param">newValue</a>,
    <a href="../memoryorder-06/index.md" class="code_type">MemoryOrder</a> <a href="store.md#decl-order" class="code_param">order</a>)
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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
