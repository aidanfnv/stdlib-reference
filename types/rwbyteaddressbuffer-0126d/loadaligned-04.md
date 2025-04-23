---
layout: stdlib-reference
---

# RWByteAddressBuffer\.LoadAligned

## Description

Load an element with type <span class='code'><a href="loadaligned-04.md#typeparam-T" class="code_type">T</a></span> from the buffer at the specified location with alignment of <span class='code'><a href="loadaligned-04.md#typeparam-T" class="code_type">T</a></span>.



## Signature 

<pre>
<a href="loadaligned-04.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="loadaligned-04.md">LoadAligned</a>&lt;<a href="loadaligned-04.md#typeparam-T" class="code_type">T</a>&gt;(<span class="code_keyword">int</span> <a href="loadaligned-04.md#decl-location" class="code_param">location</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T

## Parameters

####  <a id="decl-location"></a>location  : int
The input address in bytes which must be a multiple of size of <span class='code'><a href="loadaligned-04.md#typeparam-T" class="code_type">T</a></span>.


## Return value
T value with type <span class='code'><a href="loadaligned-04.md#typeparam-T" class="code_type">T</a></span> loaded from the buffer.

## Remarks

Currently, this function only supports when <span class='code'><a href="loadaligned-04.md#typeparam-T" class="code_type">T</a></span> is scalar, vector, or matrix type.


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
