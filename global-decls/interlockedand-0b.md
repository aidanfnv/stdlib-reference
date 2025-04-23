---
layout: stdlib-reference
---

# InterlockedAnd

## Description

Perform an atomic and operation on <span class='code'><a href="interlockedand-0b.md#decl-dest" class="code_param">dest</a></span>.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="interlockedand-0b.md">InterlockedAnd</a>&lt;<a href="interlockedand-0b.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="interlockedand-0b.md#typeparam-T" class="code_type">T</a> <a href="interlockedand-0b.md#decl-dest" class="code_param">dest</a>,
    <a href="interlockedand-0b.md#typeparam-T" class="code_type">T</a> <a href="interlockedand-0b.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="interlockedand-0b.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/iarithmeticatomicable-01b/index.md" class="code_type">IArithmeticAtomicable</a>;

<span class="code_keyword">void</span> <a href="interlockedand-0b.md">InterlockedAnd</a>&lt;<a href="interlockedand-0b.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="interlockedand-0b.md#typeparam-T" class="code_type">T</a> <a href="interlockedand-0b.md#decl-dest" class="code_param">dest</a>,
    <a href="interlockedand-0b.md#typeparam-T" class="code_type">T</a> <a href="interlockedand-0b.md#decl-value" class="code_param">value</a>,
    <span class="code_keyword">out</span> <a href="interlockedand-0b.md#typeparam-T" class="code_type">T</a> <a href="interlockedand-0b.md#decl-original_value" class="code_param">original_value</a>)
    <span class='code_keyword'>where</span> <a href="interlockedand-0b.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/iarithmeticatomicable-01b/index.md" class="code_type">IArithmeticAtomicable</a>;

<span class="code_keyword">void</span> <a href="interlockedand-0b.md">InterlockedAnd</a>(
    <span class="code_keyword">uint</span> <a href="interlockedand-0b.md#decl-dest" class="code_param">dest</a>,
    <span class="code_keyword">int</span> <a href="interlockedand-0b.md#decl-value" class="code_param">value</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [IArithmeticAtomicable](../interfaces/iarithmeticatomicable-01b/index.md)
The type of the value to perform the atomic operation on.


## Parameters

####  <a id="decl-dest"></a>dest  : [T](interlockedand-0b.md#typeparam-T)
The value to perform the atomic operation on.

####  <a id="decl-value"></a>value  : [T](interlockedand-0b.md#typeparam-T)
The operand to the atomic operation.

####  <a id="decl-original_value"></a>original\_value  : [T](interlockedand-0b.md#typeparam-T)
The value of <span class='code'><a href="interlockedand-0b.md#decl-dest" class="code_param">dest</a></span> before the operation.

####  <a id="decl-dest"></a>dest  : uint
The value to perform the atomic operation on.

####  <a id="decl-value"></a>value  : int
The operand to the atomic operation.


## Remarks
When targeting HLSL, it is invalid to call this function with <span class='code'><a href="interlockedand-0b.md#typeparam-T" class="code_type">T</a></span> being a floating-point type, since
HLSL does not allow atomic operations on floating point types. For <span class='code'><a href="interlockedadd-0b.md">InterlockedAdd</a></span>, consider using
<span class='code'><a href="../types/rwbyteaddressbuffer-0126d/index.md" class="code_type">RWByteAddressBuffer</a>.<a href="../types/rwbyteaddressbuffer-0126d/interlockedaddf32-0be.md">InterlockedAddF32</a></span> or <span class='code'><a href="../types/rwbyteaddressbuffer-0126d/index.md" class="code_type">RWByteAddressBuffer</a>.<a href="../types/rwbyteaddressbuffer-0126d/interlockedaddf16-0be.md">InterlockedAddF16</a></span> instead when NVAPI is available.
On SPIR-V (Vulkan), all integer and floating point types are supported.
On Metal and WGSL, all floating-point types are not supported.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
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
