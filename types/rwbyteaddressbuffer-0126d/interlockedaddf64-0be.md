---
layout: stdlib-reference
---

# RWByteAddressBuffer\.InterlockedAddF64

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="interlockedaddf64-0be.md">InterlockedAddF64</a>(
    <span class="code_keyword">uint</span> <a href="interlockedaddf64-0be.md#decl-byteAddress" class="code_param">byteAddress</a>,
    <span class="code_keyword">double</span> <a href="interlockedaddf64-0be.md#decl-valueToAdd" class="code_param">valueToAdd</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">double</span> <a href="interlockedaddf64-0be.md#decl-originalValue" class="code_param">originalValue</a>);

</pre>

## Parameters

####  <a id="decl-byteAddress"></a>byteAddress  : uint
####  <a id="decl-valueToAdd"></a>valueToAdd  : double
####  <a id="decl-originalValue"></a>originalValue  : double

## Availability and Requirements

Defined for the following targets:

#### cuda
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvAtomicFloat64AddEXT`.



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
