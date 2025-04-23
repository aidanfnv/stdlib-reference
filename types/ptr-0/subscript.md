---
layout: stdlib-reference
---

# Ptr\<T, addrSpace:uint64\_t\>\.subscript

## Description





## Signature 

<pre>
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">Ptr</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-addrSpace" class="code_var">addrSpace</a>:uint64_t&gt;.<a href="subscript.md">subscript</a>&lt;<a href="subscript.md#typeparam-TInt" class="code_type">TInt</a>&gt;(
    <a href="subscript.md#typeparam-TInt" class="code_type">TInt</a> <a href="subscript.md#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="subscript.md#typeparam-TInt" class="code_type">TInt</a> : <a href="../../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-TInt"></a>TInt: [\_\_BuiltinIntegerType](../../interfaces/0_builtinintegertype-029g/index.md)

## Parameters

####  <a id="decl-index"></a>index  : [TInt](subscript.md#typeparam-TInt)


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
