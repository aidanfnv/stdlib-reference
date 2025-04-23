---
layout: stdlib-reference
---

# RWByteAddressBuffer\.StoreByteOffset

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="storebyteoffset-059.md">StoreByteOffset</a>&lt;<a href="storebyteoffset-059.md#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">int</span> <a href="storebyteoffset-059.md#decl-offset" class="code_param">offset</a>,
    <a href="storebyteoffset-059.md#typeparam-T" class="code_type">T</a> <a href="storebyteoffset-059.md#decl-element" class="code_param">element</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T

## Parameters

####  <a id="decl-offset"></a>offset  : int
####  <a id="decl-element"></a>element  : [T](storebyteoffset-059.md#typeparam-T)


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
