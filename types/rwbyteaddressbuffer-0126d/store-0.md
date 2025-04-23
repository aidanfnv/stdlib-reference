---
layout: stdlib-reference
---

# RWByteAddressBuffer\.Store

## Description

Set one value to the buffer at the specified location.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="store-0.md">Store</a>(
    <span class="code_keyword">uint</span> <a href="store-0.md#decl-address" class="code_param">address</a>,
    <span class="code_keyword">uint</span> <a href="store-0.md#decl-value" class="code_param">value</a>);

<span class="code_keyword">void</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="store-0.md">Store</a>&lt;<a href="store-0.md#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">uint</span> <a href="store-0.md#decl-address" class="code_param">address</a>,
    <a href="store-0.md#typeparam-T" class="code_type">T</a> <a href="store-0.md#decl-value" class="code_param">value</a>);

<span class="code_keyword">void</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="store-0.md">Store</a>&lt;<a href="store-0.md#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">uint</span> <a href="store-0.md#decl-address" class="code_param">address</a>,
    <a href="store-0.md#typeparam-T" class="code_type">T</a> <a href="store-0.md#decl-value" class="code_param">value</a>,
    <span class="code_keyword">uint</span> <a href="store-0.md#decl-alignment" class="code_param">alignment</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T
The type of the value to load from the buffer.


## Parameters

####  <a id="decl-address"></a>address  : uint
The input address in bytes, which must be a multiple of 4.

####  <a id="decl-value"></a>value  : uint
The input value.

####  <a id="decl-value"></a>value  : [T](store-0.md#typeparam-T)
The input value.

####  <a id="decl-alignment"></a>alignment  : uint
Specifies the alignment of the location, which must be a multiple of 4.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### spirv
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
