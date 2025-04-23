---
layout: stdlib-reference
---

# Atomic\<T\>\.add

## Description

Atomically adds the given value to the stored value and returns the
original stored value.




## Signature 

<pre>
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">Atomic</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="add.md">add</a>(
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="add.md#decl-value" class="code_param">value</a>,
    <a href="../memoryorder-06/index.md" class="code_type">MemoryOrder</a> <a href="add.md#decl-order" class="code_param">order</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/iarithmeticatomicable-01b/index.md" class="code_type">IArithmeticAtomicable</a>;

</pre>

## Parameters

####  <a id="decl-value"></a>value  : [T](index.md#typeparam-T)
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
