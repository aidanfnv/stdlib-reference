---
layout: stdlib-reference
---

# InterlockedCompareStoreFloatBitwise

## Description

Perform an atomic compare and store operation on <span class='code'><a href=".html#decl-dest" class="code_param">dest</a></span>.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href=".html">InterlockedCompareStoreFloatBitwise</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>&gt;(
    <a href=".html#typeparam-T" class="code_type">T</a> <a href=".html#decl-dest" class="code_param">dest</a>,
    <a href=".html#typeparam-T" class="code_type">T</a> <a href=".html#decl-compare_value" class="code_param">compare_value</a>,
    <a href=".html#typeparam-T" class="code_type">T</a> <a href=".html#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/iatomicable-01/index.html" class="code_type">IAtomicable</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [IAtomicable](../../interfaces/iatomicable-01/index.html)
The type of the value to perform the atomic operation on.


## Parameters

####  <a id="decl-dest"></a>dest  : [T](.html#typeparam-T)
The value to perform the atomic operation on.

####  <a id="decl-compare_value"></a>compare\_value  : [T](.html#typeparam-T)
The value to compare <span class='code'><a href=".html#decl-dest" class="code_param">dest</a></span> with.

####  <a id="decl-value"></a>value  : [T](.html#typeparam-T)
The value to store into <span class='code'><a href=".html#decl-dest" class="code_param">dest</a></span> if the compare result is equal.


## Remarks
When targeting HLSL, a call to this function will translate to a call to
<span class='code'><a href=".html">InterlockedCompareStoreFloatBitwise</a></span>, which means the comparison is done as a bitwise comparison.

On SPIR-V (Vulkan), this function maps to <span class='code'>OpAtomicCompareExchange</span>.

On Metal and WGSL, this function is not available.

On CUDA, this function maps to <span class='code'>atomicCAS</span>.


