---
layout: stdlib-reference
---

# RWByteAddressBuffer\.InterlockedOr64

## Description

Perform a 64-bit integer atomic or operation at <span class='code'><a href="interlockedor64-0b.md#decl-byteAddress" class="code_param">byteAddress</a></span>.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="interlockedor64-0b.md">InterlockedOr64</a>(
    <span class="code_keyword">uint</span> <a href="interlockedor64-0b.md#decl-byteAddress" class="code_param">byteAddress</a>,
    int64_t <a href="interlockedor64-0b.md#decl-value" class="code_param">value</a>);

<span class="code_keyword">void</span> <a href="index.md" class="code_type">RWByteAddressBuffer</a>.<a href="interlockedor64-0b.md">InterlockedOr64</a>&lt;<a href="interlockedor64-0b.md#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">uint</span> <a href="interlockedor64-0b.md#decl-byteAddress" class="code_param">byteAddress</a>,
    <a href="interlockedor64-0b.md#typeparam-T" class="code_type">T</a> <a href="interlockedor64-0b.md#decl-value" class="code_param">value</a>,
    <span class="code_keyword">out</span> <a href="interlockedor64-0b.md#typeparam-T" class="code_type">T</a> <a href="interlockedor64-0b.md#decl-outOriginalValue" class="code_param">outOriginalValue</a>)
    <span class='code_keyword'>where</span> <a href="interlockedor64-0b.md#typeparam-T" class="code_type">T</a> : __BuiltinInt64Type;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: \_\_BuiltinInt64Type

## Parameters

####  <a id="decl-byteAddress"></a>byteAddress  : uint
The address at which to perform the atomic or operation.

####  <a id="decl-value"></a>value  : int64\_t
The operand for the or operation.

####  <a id="decl-value"></a>value  : [T](interlockedor64-0b.md#typeparam-T)
The operand for the or operation.

####  <a id="decl-outOriginalValue"></a>outOriginalValue  : [T](interlockedor64-0b.md#typeparam-T)
The original value at <span class='code'><a href="interlockedor64-0b.md#decl-byteAddress" class="code_param">byteAddress</a></span> before the or operation.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvInt64Atomics`.



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
