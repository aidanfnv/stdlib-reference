---
layout: stdlib-reference
---

# RWByteAddressBuffer\.StoreAligned

## Description

Set four values to the buffer at the specified location, the address will be aligned
to the alignment of <span class='code'><a href="storealigned-05.md#typeparam-T" class="code_type">T</a></span>.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="storealigned-05.md">StoreAligned</a>&lt;<a href="storealigned-05.md#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">uint</span> <a href="storealigned-05.md#decl-address" class="code_param">address</a>,
    <a href="storealigned-05.md#typeparam-T" class="code_type">T</a> <a href="storealigned-05.md#decl-value" class="code_param">value</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T
The type of the input value.


## Parameters

####  <a id="decl-address"></a>address  : uint
The input address in bytes, which must be a multiple of size of <span class='code'><a href="storealigned-05.md#typeparam-T" class="code_type">T</a></span>.

####  <a id="decl-value"></a>value  : [T](storealigned-05.md#typeparam-T)
The input value.



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
