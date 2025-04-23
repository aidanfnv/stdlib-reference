---
layout: stdlib-reference
---

# loadAligned

## Description

Load a value from a pointer with a known alignment.
Aligned loads are more efficient than unaligned loads on some platforms.



## Signature 

<pre>
<a href="loadaligned-4.md#typeparam-T" class="code_type">T</a> <a href="loadaligned-4.md">loadAligned</a>&lt;<a href="loadaligned-4.md#decl-alignment" class="code_var">alignment</a>:<span class="code_keyword">int</span>, <a href="loadaligned-4.md#typeparam-T" class="code_type">T</a>&gt;(<a href="../types/ptr-0/index.md" class="code_type">Ptr</a>&lt;<a href="loadaligned-4.md#typeparam-T" class="code_type">T</a>&gt; <a href="loadaligned-4.md#decl-ptr" class="code_param">ptr</a>);

</pre>

## Generic Parameters

####  <a id="decl-alignment"></a>alignment  : int
The alignment of the load operation.

####  <a id="typeparam-T"></a>T

## Parameters

####  <a id="decl-ptr"></a>ptr  : [Ptr](../types/ptr-0/index.md)\<[T](../types/ptr-0/index.md#typeparam-T)\>
The pointer to load from.


## Return value
The value loaded from the pointer.

## Remarks
When targeting SPIRV, this function maps to an <span class='code'>OpLoad</span> instruction with the <span class='code'>Aligned</span> memory operand.
The functions maps to normal load operation on other targets.



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
