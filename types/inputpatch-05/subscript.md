---
layout: stdlib-reference
---

# InputPatch\<T, N:int\>\.subscript

## Description





## Signature 

<pre>
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">InputPatch</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="subscript.md">subscript</a>&lt;<a href="subscript.md#typeparam-TIndex" class="code_type">TIndex</a>&gt;(<a href="subscript.md#typeparam-TIndex" class="code_type">TIndex</a> <a href="subscript.md#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="subscript.md#typeparam-TIndex" class="code_type">TIndex</a> : <a href="../../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-TIndex"></a>TIndex: [\_\_BuiltinIntegerType](../../interfaces/0_builtinintegertype-029g/index.md)

## Parameters

####  <a id="decl-index"></a>index  : [TIndex](subscript.md#typeparam-TIndex)


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
