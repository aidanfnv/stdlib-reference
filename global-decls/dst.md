---
layout: stdlib-reference
---

# dst

## Description

Helper for computing distance terms for lighting (obsolete).
Use the subtraction operator '-' instead.




## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="dst.md#typeparam-T" class="code_type">T</a>, 4&gt; <a href="dst.md">dst</a>&lt;<a href="dst.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="dst.md#typeparam-T" class="code_type">T</a>, 4&gt; <a href="dst.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="dst.md#typeparam-T" class="code_type">T</a>, 4&gt; <a href="dst.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="dst.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)

## Parameters

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), 4\>
####  <a id="decl-y"></a>y  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), 4\>


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
