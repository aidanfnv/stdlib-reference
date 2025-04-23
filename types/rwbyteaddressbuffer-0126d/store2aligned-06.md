---
layout: stdlib-reference
---

# RWByteAddressBuffer\.Store2Aligned

## Description

Set two values to the buffer at the specified location, the address will be aligned
to the alignment of  <span class='code'>uint2</span>, which is 8.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="store2aligned-06.md">Store2Aligned</a>(
    <span class="code_keyword">uint</span> <a href="store2aligned-06.md#decl-address" class="code_param">address</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 2&gt; <a href="store2aligned-06.md#decl-value" class="code_param">value</a>);

</pre>

## Parameters

####  <a id="decl-address"></a>address  : uint
The input address in bytes, which must be a multiple of 8.

####  <a id="decl-value"></a>value  : [vector](../vector/index.md)\<uint, 2\>
Two input values.


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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
