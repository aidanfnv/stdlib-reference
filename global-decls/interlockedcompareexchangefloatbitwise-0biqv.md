---
layout: stdlib-reference
---

# InterlockedCompareExchangeFloatBitwise

## Description

Perform an atomic compare and exchange operation on <span class='code'><a href="interlockedcompareexchangefloatbitwise-0biqv.md#decl-dest" class="code_param">dest</a></span>.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="interlockedcompareexchangefloatbitwise-0biqv.md">InterlockedCompareExchangeFloatBitwise</a>(
    <span class="code_keyword">float</span> <a href="interlockedcompareexchangefloatbitwise-0biqv.md#decl-dest" class="code_param">dest</a>,
    <span class="code_keyword">float</span> <a href="interlockedcompareexchangefloatbitwise-0biqv.md#decl-compare_value" class="code_param">compare_value</a>,
    <span class="code_keyword">float</span> <a href="interlockedcompareexchangefloatbitwise-0biqv.md#decl-value" class="code_param">value</a>);

<span class="code_keyword">void</span> <a href="interlockedcompareexchangefloatbitwise-0biqv.md">InterlockedCompareExchangeFloatBitwise</a>(
    <span class="code_keyword">float</span> <a href="interlockedcompareexchangefloatbitwise-0biqv.md#decl-dest" class="code_param">dest</a>,
    <span class="code_keyword">float</span> <a href="interlockedcompareexchangefloatbitwise-0biqv.md#decl-compare_value" class="code_param">compare_value</a>,
    <span class="code_keyword">float</span> <a href="interlockedcompareexchangefloatbitwise-0biqv.md#decl-value" class="code_param">value</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">float</span> <a href="interlockedcompareexchangefloatbitwise-0biqv.md#decl-original_value" class="code_param">original_value</a>);

</pre>

## Parameters

####  <a id="decl-dest"></a>dest  : float
The value to perform the atomic operation on.

####  <a id="decl-compare_value"></a>compare\_value  : float
The value to compare <span class='code'><a href="interlockedcompareexchangefloatbitwise-0biqv.md#decl-dest" class="code_param">dest</a></span> with.

####  <a id="decl-value"></a>value  : float
The value to store into <span class='code'><a href="interlockedcompareexchangefloatbitwise-0biqv.md#decl-dest" class="code_param">dest</a></span> if the compare result is equal.

####  <a id="decl-original_value"></a>original\_value  : float
The value of <span class='code'><a href="interlockedcompareexchangefloatbitwise-0biqv.md#decl-dest" class="code_param">dest</a></span> before the operation.


## Remarks
When targeting HLSL, a call to this function will translate to a call to
<span class='code'><a href="interlockedcompareexchangefloatbitwise-0biqv.md">InterlockedCompareExchangeFloatBitwise</a></span>, which means the comparison is done as a bitwise comparison.

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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
