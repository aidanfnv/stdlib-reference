---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.SampleCmpLevel

## Description





## Signature 

<pre>
/// Requires Capability Set 1:
<span class="code_keyword">float</span> <a href="../types/0texture-01/index.html" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a>&gt;.<a href="samplecmplevel-069.html">SampleCmpLevel</a>(
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplecmplevel-069.html#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevel-069.html#decl-compareValue" class="code_param">compareValue</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevel-069.html#decl-level" class="code_param">level</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index.html" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 1:
<span class="code_keyword">float</span> <a href="../types/0texture-01/index.html" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a>&gt;.<a href="samplecmplevel-069.html">SampleCmpLevel</a>(
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplecmplevel-069.html#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevel-069.html#decl-compareValue" class="code_param">compareValue</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevel-069.html#decl-level" class="code_param">level</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="samplecmplevel-069.html#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index.html" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 2:
<span class="code_keyword">float</span> <a href="../types/0texture-01/index.html" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a>&gt;.<a href="samplecmplevel-069.html">SampleCmpLevel</a>(
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplecmplevel-069.html#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevel-069.html#decl-compareValue" class="code_param">compareValue</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevel-069.html#decl-level" class="code_param">level</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="samplecmplevel-069.html#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="samplecmplevel-069.html#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index.html" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 1:
<span class="code_keyword">float</span> <a href="../types/0texture-01/index.html" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a>&gt;.<a href="samplecmplevel-069.html">SampleCmpLevel</a>(
    <a href="../types/samplercomparisonstate-07h/index.html" class="code_type">SamplerComparisonState</a> <a href="samplecmplevel-069.html#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplecmplevel-069.html#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevel-069.html#decl-compareValue" class="code_param">compareValue</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevel-069.html#decl-level" class="code_param">level</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index.html" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 1:
<span class="code_keyword">float</span> <a href="../types/0texture-01/index.html" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a>&gt;.<a href="samplecmplevel-069.html">SampleCmpLevel</a>(
    <a href="../types/samplercomparisonstate-07h/index.html" class="code_type">SamplerComparisonState</a> <a href="samplecmplevel-069.html#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplecmplevel-069.html#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevel-069.html#decl-compareValue" class="code_param">compareValue</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevel-069.html#decl-level" class="code_param">level</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="samplecmplevel-069.html#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index.html" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 2:
<span class="code_keyword">float</span> <a href="../types/0texture-01/index.html" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a>&gt;.<a href="samplecmplevel-069.html">SampleCmpLevel</a>(
    <a href="../types/samplercomparisonstate-07h/index.html" class="code_type">SamplerComparisonState</a> <a href="samplecmplevel-069.html#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplecmplevel-069.html#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevel-069.html#decl-compareValue" class="code_param">compareValue</a>,
    <span class="code_keyword">float</span> <a href="samplecmplevel-069.html#decl-level" class="code_param">level</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="samplecmplevel-069.html#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="samplecmplevel-069.html#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index.html" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

####  <a id="decl-location"></a>location  : [vector](../types/vector/index.html)\<float, isArray + Shape\.dimensions\>
####  <a id="decl-compareValue"></a>compareValue  : float
####  <a id="decl-level"></a>level  : float
####  <a id="decl-offset"></a>offset  : [vector](../types/vector/index.html)\<int, Shape\.planeDimensions\>
####  <a id="decl-status"></a>status  : uint
####  <a id="decl-s"></a>s  : [SamplerComparisonState](../types/samplercomparisonstate-07h/index.html)

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### metal
Available in all stages.

#### spirv
Available in all stages.


### Capability Set 2

Defined for the following targets:

#### hlsl
Available in all stages.

#### spirv
Available in all stages.



