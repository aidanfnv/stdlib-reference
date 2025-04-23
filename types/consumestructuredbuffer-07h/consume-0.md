---
layout: stdlib-reference
---

# ConsumeStructuredBuffer\<T, L\>\.Consume

## Description

Reading the element at the end of the buffer indicated by the associated atomic counter
and decrement the builtin atomic counter by 1.



## Signature 

<pre>
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">ConsumeStructuredBuffer</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-L" class="code_type">L</a>&gt;.<a href="consume-0.md">Consume</a>()
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-L" class="code_type">L</a> : <a href="../../interfaces/ibufferdatalayout-017b/index.md" class="code_type">IBufferDataLayout</a>;

</pre>

## Return value
The element read from the buffer, it can be a structure.



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
