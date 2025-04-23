---
layout: stdlib-reference
---

# TorchTensor\<T\>\.size

## Description





## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="index.md" class="code_type">TorchTensor</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="size.md">size</a>(<span class="code_keyword">uint</span> <a href="size.md#decl-i" class="code_param">i</a>);

</pre>

## Parameters

####  <a id="decl-i"></a>i  : uint

## Availability and Requirements

Defined for the following targets:

#### cpp
Available in all stages.

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
