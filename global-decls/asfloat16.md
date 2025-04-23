---
layout: stdlib-reference
---

# asfloat16

## Description

Reinterpret bits as a float16 (HLSL SM 6.2).




## Signature 

<pre>
<span class="code_keyword">half</span> <a href="asfloat16.md">asfloat16</a>(<span class="code_keyword">half</span> <a href="asfloat16.md#decl-value" class="code_param">value</a>);

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">half</span>, <a href="asfloat16.md#decl-N" class="code_var">N</a>&gt; <a href="asfloat16.md">asfloat16</a>&lt;<a href="asfloat16.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">half</span>, <a href="asfloat16.md#decl-N" class="code_var">N</a>&gt; <a href="asfloat16.md#decl-value" class="code_param">value</a>);

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<span class="code_keyword">half</span>, <a href="asfloat16.md#decl-R" class="code_var">R</a>, <a href="asfloat16.md#decl-C" class="code_var">C</a>&gt; <a href="asfloat16.md">asfloat16</a>&lt;<a href="asfloat16.md#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href="asfloat16.md#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<span class="code_keyword">half</span>, <a href="asfloat16.md#decl-R" class="code_var">R</a>, <a href="asfloat16.md#decl-C" class="code_var">C</a>&gt; <a href="asfloat16.md#decl-value" class="code_param">value</a>);

/// Requires Capability Set 1:
<span class="code_keyword">half</span> <a href="asfloat16.md">asfloat16</a>(uint16_t <a href="asfloat16.md#decl-value" class="code_param">value</a>);

/// Requires Capability Set 1:
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">half</span>, <a href="asfloat16.md#decl-N" class="code_var">N</a>&gt; <a href="asfloat16.md">asfloat16</a>&lt;<a href="asfloat16.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;uint16_t, <a href="asfloat16.md#decl-N" class="code_var">N</a>&gt; <a href="asfloat16.md#decl-value" class="code_param">value</a>);

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<span class="code_keyword">half</span>, <a href="asfloat16.md#decl-R" class="code_var">R</a>, <a href="asfloat16.md#decl-C" class="code_var">C</a>&gt; <a href="asfloat16.md">asfloat16</a>&lt;<a href="asfloat16.md#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href="asfloat16.md#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;uint16_t, <a href="asfloat16.md#decl-R" class="code_var">R</a>, <a href="asfloat16.md#decl-C" class="code_var">C</a>&gt; <a href="asfloat16.md#decl-value" class="code_param">value</a>);

/// Requires Capability Set 2:
<span class="code_keyword">half</span> <a href="asfloat16.md">asfloat16</a>(int16_t <a href="asfloat16.md#decl-value" class="code_param">value</a>);

/// Requires Capability Set 2:
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">half</span>, <a href="asfloat16.md#decl-N" class="code_var">N</a>&gt; <a href="asfloat16.md">asfloat16</a>&lt;<a href="asfloat16.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;int16_t, <a href="asfloat16.md#decl-N" class="code_var">N</a>&gt; <a href="asfloat16.md#decl-value" class="code_param">value</a>);

/// Requires Capability Set 3:
<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<span class="code_keyword">half</span>, <a href="asfloat16.md#decl-R" class="code_var">R</a>, <a href="asfloat16.md#decl-C" class="code_var">C</a>&gt; <a href="asfloat16.md">asfloat16</a>&lt;<a href="asfloat16.md#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href="asfloat16.md#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;int16_t, <a href="asfloat16.md#decl-R" class="code_var">R</a>, <a href="asfloat16.md#decl-C" class="code_var">C</a>&gt; <a href="asfloat16.md#decl-value" class="code_param">value</a>);

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int
####  <a id="decl-R"></a>R  : int
####  <a id="decl-C"></a>C  : int

## Parameters

####  <a id="decl-value"></a>value  : half
####  <a id="decl-value"></a>value  : [vector](../types/vector/index.md)\<half, [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-value"></a>value  : [matrix](../types/matrix/index.md)\<half, [R](../types/matrix/index.md#decl-R), [C](../types/matrix/index.md#decl-C)\>
####  <a id="decl-value"></a>value  : uint16\_t
####  <a id="decl-value"></a>value  : [vector](../types/vector/index.md)\<uint16\_t, [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-value"></a>value  : [matrix](../types/matrix/index.md)\<uint16\_t, [R](../types/matrix/index.md#decl-R), [C](../types/matrix/index.md#decl-C)\>
####  <a id="decl-value"></a>value  : int16\_t
####  <a id="decl-value"></a>value  : [vector](../types/vector/index.md)\<int16\_t, [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-value"></a>value  : [matrix](../types/matrix/index.md)\<int16\_t, [R](../types/matrix/index.md#decl-R), [C](../types/matrix/index.md#decl-C)\>

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.


### Capability Set 2

Defined for the following targets:

#### hlsl
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### spirv
Available in all stages.


### Capability Set 3

Defined for the following targets:

#### hlsl
Available in all stages.

#### cuda
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
