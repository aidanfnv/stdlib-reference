---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.CalculateLevelOfDetailUnclamped

## Description





## Signature 

<pre>
<span class="code_keyword">float</span> <a href="index.html" class="code_type">_Texture</a>&lt;<a href="index.html#typeparam-T" class="code_type">T</a>, <a href="index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="index.html#decl-isArray" class="code_var">isArray</a>, <a href="index.html#decl-isMS" class="code_var">isMS</a>, <a href="index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.html#decl-access" class="code_var">access</a>, <a href="index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="index.html#decl-format" class="code_var">format</a>&gt;.<a href="calculatelevelofdetailunclamped-09egm.html">CalculateLevelOfDetailUnclamped</a>(
    <a href="index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.html#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="calculatelevelofdetailunclamped-09egm.html#decl-location" class="code_param">location</a>)
    <span class='code_keyword'>where</span> <a href="index.html#typeparam-T" class="code_type">T</a> : <a href="index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.html#typeparam-Shape" class="code_type">Shape</a> : <a href="index.html" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.html#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.html#decl-isCombined" class="code_var">isCombined</a> == 1;

<span class="code_keyword">float</span> <a href="index.html" class="code_type">_Texture</a>&lt;<a href="index.html#typeparam-T" class="code_type">T</a>, <a href="index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="index.html#decl-isArray" class="code_var">isArray</a>, <a href="index.html#decl-isMS" class="code_var">isMS</a>, <a href="index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.html#decl-access" class="code_var">access</a>, <a href="index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="index.html#decl-format" class="code_var">format</a>&gt;.<a href="calculatelevelofdetailunclamped-09egm.html">CalculateLevelOfDetailUnclamped</a>(
    <a href="index.html" class="code_type">SamplerState</a> <a href="calculatelevelofdetailunclamped-09egm.html#decl-s" class="code_param">s</a>,
    <a href="index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.html#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="calculatelevelofdetailunclamped-09egm.html#decl-location" class="code_param">location</a>)
    <span class='code_keyword'>where</span> <a href="index.html#typeparam-T" class="code_type">T</a> : <a href="index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.html#typeparam-Shape" class="code_type">Shape</a> : <a href="index.html" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.html#decl-isCombined" class="code_var">isCombined</a> == 0;

<span class="code_keyword">float</span> <a href="index.html" class="code_type">_Texture</a>&lt;<a href="index.html#typeparam-T" class="code_type">T</a>, <a href="index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="index.html#decl-isArray" class="code_var">isArray</a>, <a href="index.html#decl-isMS" class="code_var">isMS</a>, <a href="index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.html#decl-access" class="code_var">access</a>, <a href="index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="index.html#decl-format" class="code_var">format</a>&gt;.<a href="calculatelevelofdetailunclamped-09egm.html">CalculateLevelOfDetailUnclamped</a>(
    <a href="index.html" class="code_type">SamplerComparisonState</a> <a href="calculatelevelofdetailunclamped-09egm.html#decl-s" class="code_param">s</a>,
    <a href="index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.html#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="calculatelevelofdetailunclamped-09egm.html#decl-location" class="code_param">location</a>)
    <span class='code_keyword'>where</span> <a href="index.html#typeparam-T" class="code_type">T</a> : <a href="index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.html#typeparam-Shape" class="code_type">Shape</a> : <a href="index.html" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.html#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

####  <a id="decl-location"></a>location  : [vector](../vector/index)\<float, Shape\.dimensions\>
####  <a id="decl-s"></a>s  : [SamplerState](../samplerstate-07/index)
####  <a id="decl-s"></a>s  : [SamplerComparisonState](../samplercomparisonstate-07h/index)

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### metal
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvImageQuery`.


