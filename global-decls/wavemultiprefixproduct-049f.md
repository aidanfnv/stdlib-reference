---
layout: stdlib-reference
---

# WaveMultiPrefixProduct

## Description





## Signature 

<pre>
<a href="wavemultiprefixproduct-049f.md#typeparam-T" class="code_type">T</a> <a href="wavemultiprefixproduct-049f.md">WaveMultiPrefixProduct</a>&lt;<a href="wavemultiprefixproduct-049f.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="wavemultiprefixproduct-049f.md#typeparam-T" class="code_type">T</a> <a href="wavemultiprefixproduct-049f.md#decl-value" class="code_param">value</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="wavemultiprefixproduct-049f.md#decl-mask" class="code_param">mask</a>)
    <span class='code_keyword'>where</span> <a href="wavemultiprefixproduct-049f.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="wavemultiprefixproduct-049f.md#typeparam-T" class="code_type">T</a>, <a href="wavemultiprefixproduct-049f.md#decl-N" class="code_var">N</a>&gt; <a href="wavemultiprefixproduct-049f.md">WaveMultiPrefixProduct</a>&lt;<a href="wavemultiprefixproduct-049f.md#typeparam-T" class="code_type">T</a>, <a href="wavemultiprefixproduct-049f.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="wavemultiprefixproduct-049f.md#typeparam-T" class="code_type">T</a>, <a href="wavemultiprefixproduct-049f.md#decl-N" class="code_var">N</a>&gt; <a href="wavemultiprefixproduct-049f.md#decl-value" class="code_param">value</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="wavemultiprefixproduct-049f.md#decl-mask" class="code_param">mask</a>)
    <span class='code_keyword'>where</span> <a href="wavemultiprefixproduct-049f.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="wavemultiprefixproduct-049f.md#typeparam-T" class="code_type">T</a>, <a href="wavemultiprefixproduct-049f.md#decl-N" class="code_var">N</a>, <a href="wavemultiprefixproduct-049f.md#decl-M" class="code_var">M</a>&gt; <a href="wavemultiprefixproduct-049f.md">WaveMultiPrefixProduct</a>&lt;<a href="wavemultiprefixproduct-049f.md#typeparam-T" class="code_type">T</a>, <a href="wavemultiprefixproduct-049f.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="wavemultiprefixproduct-049f.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="wavemultiprefixproduct-049f.md#typeparam-T" class="code_type">T</a>, <a href="wavemultiprefixproduct-049f.md#decl-N" class="code_var">N</a>, <a href="wavemultiprefixproduct-049f.md#decl-M" class="code_var">M</a>&gt; <a href="wavemultiprefixproduct-049f.md#decl-value" class="code_param">value</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="wavemultiprefixproduct-049f.md#decl-mask" class="code_param">mask</a>)
    <span class='code_keyword'>where</span> <a href="wavemultiprefixproduct-049f.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-value"></a>value  : [T](wavemultiprefixproduct-049f.md#typeparam-T)
####  <a id="decl-mask"></a>mask  : [vector](../types/vector/index.md)\<uint, 4\>
####  <a id="decl-value"></a>value  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-value"></a>value  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>

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

Requires capabilities: `spvGroupNonUniformBallot`, `spvGroupNonUniformArithmetic`, `spvGroupNonUniformPartitionedNV`.



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
