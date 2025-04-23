---
layout: stdlib-reference
---

# DiffTensorView\<T, A\>\.init

## Description





## Signature 

<pre>
<a href="index.md" class="code_type">DiffTensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-A" class="code_type">A</a>&gt;.<a href="init.md">init</a>(
    <a href="../tensorview-06/index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt; <a href="init.md#decl-primal" class="code_param">primal</a>,
    <a href="index.md#typeparam-A" class="code_type">A</a> <a href="init.md#decl-diff" class="code_param">diff</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-A" class="code_type">A</a> : <a href="../../interfaces/idifftensorwrapper-015b/index.md" class="code_type">IDiffTensorWrapper</a>;

<a href="index.md" class="code_type">DiffTensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-A" class="code_type">A</a>&gt;.<a href="init.md">init</a>(<a href="../tensorview-06/index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt; <a href="init.md#decl-primal" class="code_param">primal</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-A" class="code_type">A</a> : <a href="../../interfaces/idifftensorwrapper-015b/index.md" class="code_type">IDiffTensorWrapper</a>;

</pre>

## Parameters

####  <a id="decl-primal"></a>primal  : [TensorView](../tensorview-06/index.md)\<[T](../tensorview-06/index.md#typeparam-T)\>
####  <a id="decl-diff"></a>diff  : [A](index.md#typeparam-A)


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
