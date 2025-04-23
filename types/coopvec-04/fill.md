---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.fill

## Description

Fill all elements of this CoopVec with the specified value.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="fill.md">fill</a>(<a href="index.md#typeparam-T" class="code_type">T</a> <a href="fill.md#decl-t" class="code_param">t</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Parameters

####  <a id="decl-t"></a>t  : [T](index.md#typeparam-T)
The value to fill all elements with.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvCooperativeVectorNV`.



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
