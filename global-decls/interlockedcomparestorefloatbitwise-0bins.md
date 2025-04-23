---
layout: stdlib-reference
---

# InterlockedCompareStoreFloatBitwise

## Description

Perform an atomic compare and store operation on <span class='code'><a href="interlockedcomparestorefloatbitwise-0bins.md#decl-dest" class="code_param">dest</a></span>.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="interlockedcomparestorefloatbitwise-0bins.md">InterlockedCompareStoreFloatBitwise</a>&lt;<a href="interlockedcomparestorefloatbitwise-0bins.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="interlockedcomparestorefloatbitwise-0bins.md#typeparam-T" class="code_type">T</a> <a href="interlockedcomparestorefloatbitwise-0bins.md#decl-dest" class="code_param">dest</a>,
    <a href="interlockedcomparestorefloatbitwise-0bins.md#typeparam-T" class="code_type">T</a> <a href="interlockedcomparestorefloatbitwise-0bins.md#decl-compare_value" class="code_param">compare_value</a>,
    <a href="interlockedcomparestorefloatbitwise-0bins.md#typeparam-T" class="code_type">T</a> <a href="interlockedcomparestorefloatbitwise-0bins.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="interlockedcomparestorefloatbitwise-0bins.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/iatomicable-01/index.md" class="code_type">IAtomicable</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [IAtomicable](../interfaces/iatomicable-01/index.md)
The type of the value to perform the atomic operation on.


## Parameters

####  <a id="decl-dest"></a>dest  : [T](interlockedcomparestorefloatbitwise-0bins.md#typeparam-T)
The value to perform the atomic operation on.

####  <a id="decl-compare_value"></a>compare\_value  : [T](interlockedcomparestorefloatbitwise-0bins.md#typeparam-T)
The value to compare <span class='code'><a href="interlockedcomparestorefloatbitwise-0bins.md#decl-dest" class="code_param">dest</a></span> with.

####  <a id="decl-value"></a>value  : [T](interlockedcomparestorefloatbitwise-0bins.md#typeparam-T)
The value to store into <span class='code'><a href="interlockedcomparestorefloatbitwise-0bins.md#decl-dest" class="code_param">dest</a></span> if the compare result is equal.


## Remarks
When targeting HLSL, a call to this function will translate to a call to
<span class='code'><a href="interlockedcomparestorefloatbitwise-0bins.md">InterlockedCompareStoreFloatBitwise</a></span>, which means the comparison is done as a bitwise comparison.

On SPIR-V (Vulkan), this function maps to <span class='code'>OpAtomicCompareExchange</span>.

On Metal and WGSL, this function is not available.

On CUDA, this function maps to <span class='code'>atomicCAS</span>.



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
