---
layout: stdlib-reference
---

# RasterizerOrderedStructuredBuffer\<T, L\>\.IncrementCounter

## Description

Increment the object's hidden counter.



## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="index.md" class="code_type">RasterizerOrderedStructuredBuffer</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-L" class="code_type">L</a>&gt;.<a href="incrementcounter-09.md">IncrementCounter</a>()
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-L" class="code_type">L</a> : <a href="../../interfaces/ibufferdatalayout-017b/index.md" class="code_type">IBufferDataLayout</a>;

</pre>

## Return value
The pre-incremented counter value.

## Remarks

This function is not implemented when targeting non-HLSL.



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
