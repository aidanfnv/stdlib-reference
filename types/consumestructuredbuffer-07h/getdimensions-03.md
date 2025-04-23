---
layout: stdlib-reference
---

# ConsumeStructuredBuffer\<T, L\>\.GetDimensions

## Description

Gets the dimensions of the resource.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">ConsumeStructuredBuffer</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-L" class="code_type">L</a>&gt;.<a href="getdimensions-03.md">GetDimensions</a>(
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="getdimensions-03.md#decl-numStructs" class="code_param">numStructs</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="getdimensions-03.md#decl-stride" class="code_param">stride</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-L" class="code_type">L</a> : <a href="../../interfaces/ibufferdatalayout-017b/index.md" class="code_type">IBufferDataLayout</a>;

</pre>

## Parameters

####  <a id="decl-numStructs"></a>numStructs  : uint
\[out\] The number of structures in the buffer.

####  <a id="decl-stride"></a>stride  : uint
\[out\] The stride, in bytes, of each element



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
