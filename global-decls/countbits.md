---
layout: stdlib-reference
---

# countbits

## Description

Population count.
Counts the number of set bits in the binary representation of a value.



## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="countbits.md">countbits</a>&lt;<a href="countbits.md#typeparam-T" class="code_type">T</a>&gt;(<a href="countbits.md#typeparam-T" class="code_type">T</a> <a href="countbits.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="countbits.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="countbits.md#decl-N" class="code_var">N</a>&gt; <a href="countbits.md">countbits</a>&lt;<a href="countbits.md#typeparam-T" class="code_type">T</a>, <a href="countbits.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="countbits.md#typeparam-T" class="code_type">T</a>, <a href="countbits.md#decl-N" class="code_var">N</a>&gt; <a href="countbits.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="countbits.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinIntegerType](../interfaces/0_builtinintegertype-029g/index.md)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-value"></a>value  : [T](countbits.md#typeparam-T)
The value to count bits in.

####  <a id="decl-value"></a>value  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The value to count bits in.


## Return value
The number of bits in the binary representation of <span class='code'><a href="countbits.md#decl-value" class="code_param">value</a></span> that are set to one.

## Remarks
For SPIR-V, this function maps to <span class='code'>OpBitCount</span>.


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

#### wgsl
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
