---
layout: stdlib-reference
---

# TorchTensor\<T\>\.fillValue

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">TorchTensor</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="fillvalue-4.md">fillValue</a>(<a href="index.md#typeparam-T" class="code_type">T</a> <a href="fillvalue-4.md#decl-val" class="code_param">val</a>);

</pre>

## Parameters

####  <a id="decl-val"></a>val  : [T](index.md#typeparam-T)

## Availability and Requirements

Defined for the following targets:

#### cpp
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
