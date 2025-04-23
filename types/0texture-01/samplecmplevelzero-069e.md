---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.SampleCmpLevelZero

## Description





## Signature 

<pre>
/// Requires Capability Set 1:
<span class="code_keyword">float</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplecmplevelzero-069e.md">SampleCmpLevelZero</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplecmplevelzero-069e.md#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevelzero-069e.md#decl-compareValue" class="code_param">compareValue</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 1:
<span class="code_keyword">float</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplecmplevelzero-069e.md">SampleCmpLevelZero</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplecmplevelzero-069e.md#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevelzero-069e.md#decl-compareValue" class="code_param">compareValue</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="samplecmplevelzero-069e.md#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 2:
<span class="code_keyword">float</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplecmplevelzero-069e.md">SampleCmpLevelZero</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplecmplevelzero-069e.md#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevelzero-069e.md#decl-compareValue" class="code_param">compareValue</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="samplecmplevelzero-069e.md#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="samplecmplevelzero-069e.md#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 1:
<span class="code_keyword">float</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplecmplevelzero-069e.md">SampleCmpLevelZero</a>(
    <a href="../samplercomparisonstate-07h/index.md" class="code_type">SamplerComparisonState</a> <a href="samplecmplevelzero-069e.md#decl-s" class="code_param">s</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplecmplevelzero-069e.md#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevelzero-069e.md#decl-compareValue" class="code_param">compareValue</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 1:
<span class="code_keyword">float</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplecmplevelzero-069e.md">SampleCmpLevelZero</a>(
    <a href="../samplercomparisonstate-07h/index.md" class="code_type">SamplerComparisonState</a> <a href="samplecmplevelzero-069e.md#decl-s" class="code_param">s</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplecmplevelzero-069e.md#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevelzero-069e.md#decl-compareValue" class="code_param">compareValue</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="samplecmplevelzero-069e.md#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 2:
<span class="code_keyword">float</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplecmplevelzero-069e.md">SampleCmpLevelZero</a>(
    <a href="../samplercomparisonstate-07h/index.md" class="code_type">SamplerComparisonState</a> <a href="samplecmplevelzero-069e.md#decl-s" class="code_param">s</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplecmplevelzero-069e.md#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevelzero-069e.md#decl-compareValue" class="code_param">compareValue</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="samplecmplevelzero-069e.md#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="samplecmplevelzero-069e.md#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

####  <a id="decl-location"></a>location  : [vector](../vector/index.md)\<float, isArray + Shape\.dimensions\>
####  <a id="decl-compareValue"></a>compareValue  : float
####  <a id="decl-offset"></a>offset  : [vector](../vector/index.md)\<int, Shape\.planeDimensions\>
####  <a id="decl-status"></a>status  : uint
####  <a id="decl-s"></a>s  : [SamplerComparisonState](../samplercomparisonstate-07h/index.md)

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### metal
Available in all stages.

#### wgsl
Available in all stages.

#### spirv
Available in all stages.


### Capability Set 2

Defined for the following targets:

#### hlsl
Available in all stages.

#### spirv
Available in all stages.

Requires capabilities: `SPV_KHR_non_semantic_info`, `SPV_GOOGLE_user_type`, `spvDerivativeControl`, `spvImageQuery`, `spvImageGatherExtended`, `spvSparseResidency`, `spvMinLod`, `spvFragmentFullyCoveredEXT`.



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
