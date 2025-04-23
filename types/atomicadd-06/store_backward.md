---
layout: stdlib-reference
---

# AtomicAdd\.store\_backward

## Description





## Signature 

<pre>
<a href="store_backward.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">AtomicAdd</a>.<a href="store_backward.md">store_backward</a>&lt;<a href="store_backward.md#typeparam-T" class="code_type">T</a>&gt;(<span class="code_keyword">uint</span> <a href="store_backward.md#decl-i" class="code_param">i</a>)
    <span class='code_keyword'>where</span> <a href="store_backward.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="store_backward.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">AtomicAdd</a>.<a href="store_backward.md">store_backward</a>&lt;<a href="store_backward.md#typeparam-T" class="code_type">T</a>, <a href="store_backward.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="store_backward.md#decl-N" class="code_var">N</a>&gt; <a href="store_backward.md#decl-i" class="code_param">i</a>)
    <span class='code_keyword'>where</span> <a href="store_backward.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-i"></a>i  : uint
####  <a id="decl-i"></a>i  : [vector](../vector/index.md)\<uint, [N](../vector/index.md#decl-N)\>


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
