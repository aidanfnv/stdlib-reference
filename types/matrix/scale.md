---
layout: stdlib-reference
---

# matrix\<T,R,C\>\.scale

## Description





## Signature 

<pre>
<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>, <a href="index.md#decl-M" class="code_var">M</a>&gt; <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="scale.md">scale</a>&lt;<a href="scale.md#typeparam-T1" class="code_type">T1</a>&gt;(<a href="scale.md#typeparam-T1" class="code_type">T1</a> <a href="scale.md#decl-s" class="code_param">s</a>)
    <span class='code_keyword'>where</span> <a href="scale.md#typeparam-T1" class="code_type">T1</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="t-0.md" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T1"></a>T1: [\_\_BuiltinFloatingPointType](../../interfaces/0_builtinfloatingpointtype-029hm/index.md)

## Parameters

####  <a id="decl-s"></a>s  : [T1](scale.md#typeparam-T1)


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
