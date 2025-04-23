---
layout: stdlib-reference
---

# matrix\<T,R,C\>\.equals

## Description





## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="equals.md">equals</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>, <a href="index.md#decl-M" class="code_var">M</a>&gt; <a href="equals.md#decl-other" class="code_param">other</a>)
    <span class='code_keyword'>where</span> <a href="t-0.md" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Parameters

####  <a id="decl-other"></a>other  : [matrix](index.md)\<[T](t-0.md), [N](index.md#decl-N), [M](index.md#decl-M)\>


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
