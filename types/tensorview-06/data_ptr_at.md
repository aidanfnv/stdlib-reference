---
layout: stdlib-reference
---

# TensorView\<T\>\.data\_ptr\_at

## Description





## Signature 

<pre>
<a href="../ptr-0/index.md" class="code_type">Ptr</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt; <a href="index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="data_ptr_at.md">data_ptr_at</a>(<span class="code_keyword">uint</span> <a href="data_ptr_at.md#decl-index" class="code_param">index</a>);

<a href="../ptr-0/index.md" class="code_type">Ptr</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt; <a href="index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="data_ptr_at.md">data_ptr_at</a>&lt;<a href="data_ptr_at.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="data_ptr_at.md#decl-N" class="code_var">N</a>&gt; <a href="data_ptr_at.md#decl-index" class="code_param">index</a>);

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-index"></a>index  : uint
####  <a id="decl-index"></a>index  : [vector](../vector/index.md)\<uint, [N](../vector/index.md#decl-N)\>

## Availability and Requirements

Defined for the following targets:

#### cuda
Available in all stages.




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
