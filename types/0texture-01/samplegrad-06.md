---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.SampleGrad

## Description





## Signature 

<pre>
/// Requires Capability Set 1:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplegrad-06.md">SampleGrad</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradX" class="code_param">gradX</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradY" class="code_param">gradY</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 1:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplegrad-06.md">SampleGrad</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradX" class="code_param">gradX</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradY" class="code_param">gradY</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 2:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplegrad-06.md">SampleGrad</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradX" class="code_param">gradX</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradY" class="code_param">gradY</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">float</span> <a href="samplegrad-06.md#decl-lodClamp" class="code_param">lodClamp</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 3:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplegrad-06.md">SampleGrad</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradX" class="code_param">gradX</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradY" class="code_param">gradY</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">float</span> <a href="samplegrad-06.md#decl-lodClamp" class="code_param">lodClamp</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="samplegrad-06.md#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 1:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplegrad-06.md">SampleGrad</a>(
    <a href="../samplerstate-07/index.md" class="code_type">SamplerState</a> <a href="samplegrad-06.md#decl-s" class="code_param">s</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradX" class="code_param">gradX</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradY" class="code_param">gradY</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 1:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplegrad-06.md">SampleGrad</a>(
    <a href="../samplerstate-07/index.md" class="code_type">SamplerState</a> <a href="samplegrad-06.md#decl-s" class="code_param">s</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradX" class="code_param">gradX</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradY" class="code_param">gradY</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 4:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplegrad-06.md">SampleGrad</a>(
    <a href="../samplerstate-07/index.md" class="code_type">SamplerState</a> <a href="samplegrad-06.md#decl-s" class="code_param">s</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradX" class="code_param">gradX</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradY" class="code_param">gradY</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">float</span> <a href="samplegrad-06.md#decl-lodClamp" class="code_param">lodClamp</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 3:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="samplegrad-06.md">SampleGrad</a>(
    <a href="../samplerstate-07/index.md" class="code_type">SamplerState</a> <a href="samplegrad-06.md#decl-s" class="code_param">s</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradX" class="code_param">gradX</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-gradY" class="code_param">gradY</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplegrad-06.md#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">float</span> <a href="samplegrad-06.md#decl-lodClamp" class="code_param">lodClamp</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="samplegrad-06.md#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

####  <a id="decl-location"></a>location  : [vector](../vector/index.md)\<float, isArray + Shape\.dimensions\>
####  <a id="decl-gradX"></a>gradX  : [vector](../vector/index.md)\<float, Shape\.dimensions\>
####  <a id="decl-gradY"></a>gradY  : [vector](../vector/index.md)\<float, Shape\.dimensions\>
####  <a id="decl-offset"></a>offset  : [vector](../vector/index.md)\<int, Shape\.dimensions\>
####  <a id="decl-lodClamp"></a>lodClamp  : float
####  <a id="decl-status"></a>status  : uint
####  <a id="decl-s"></a>s  : [SamplerState](../samplerstate-07/index.md)

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
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

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### metal
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvSparseResidency`.

### Capability Set 3

Defined for the following targets:

#### hlsl
Available in all stages.

#### spirv
Available in all stages.

Requires capabilities: `SPV_KHR_non_semantic_info`, `SPV_GOOGLE_user_type`, `spvDerivativeControl`, `spvImageQuery`, `spvImageGatherExtended`, `spvSparseResidency`, `spvMinLod`, `spvFragmentFullyCoveredEXT`.

### Capability Set 4

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
