---
layout: stdlib-reference
---

# AtomicAdd\.loadOnce\_backward

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">AtomicAdd</a>.<a href="loadonce_backward-4.md">loadOnce_backward</a>&lt;<a href="loadonce_backward-4.md#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">uint</span> <a href="loadonce_backward-4.md#decl-i" class="code_param">i</a>,
    <a href="loadonce_backward-4.md#typeparam-T" class="code_type">T</a> <a href="loadonce_backward-4.md#decl-dOut" class="code_param">dOut</a>)
    <span class='code_keyword'>where</span> <a href="loadonce_backward-4.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<span class="code_keyword">void</span> <a href="index.md" class="code_type">AtomicAdd</a>.<a href="loadonce_backward-4.md">loadOnce_backward</a>&lt;<a href="loadonce_backward-4.md#typeparam-T" class="code_type">T</a>, <a href="loadonce_backward-4.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="loadonce_backward-4.md#decl-N" class="code_var">N</a>&gt; <a href="loadonce_backward-4.md#decl-i" class="code_param">i</a>,
    <a href="loadonce_backward-4.md#typeparam-T" class="code_type">T</a> <a href="loadonce_backward-4.md#decl-dOut" class="code_param">dOut</a>)
    <span class='code_keyword'>where</span> <a href="loadonce_backward-4.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-i"></a>i  : uint
####  <a id="decl-dOut"></a>dOut  : [T](loadonce_backward-4.md#typeparam-T)
####  <a id="decl-i"></a>i  : [vector](../vector/index.md)\<uint, [N](../vector/index.md#decl-N)\>


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
