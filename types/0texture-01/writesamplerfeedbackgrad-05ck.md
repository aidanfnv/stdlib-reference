---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.WriteSamplerFeedbackGrad

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/0texture-01/index.html" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a>&gt;.<a href="writesamplerfeedbackgrad-05ck.html">WriteSamplerFeedbackGrad</a>&lt;<a href="writesamplerfeedbackgrad-05ck.html#typeparam-S" class="code_type">S</a>&gt;(
    <a href=".html" class="code_type">Texture2D</a>&lt;<a href="writesamplerfeedbackgrad-05ck.html#typeparam-S" class="code_type">S</a>&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-tex" class="code_param">tex</a>,
    <a href="../types/samplerstate-07/index.html" class="code_type">SamplerState</a> <a href="writesamplerfeedbackgrad-05ck.html#decl-samp" class="code_param">samp</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-location" class="code_param">location</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-ddx" class="code_param">ddx</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-ddy" class="code_param">ddy</a>,
    <span class="code_keyword">float</span> <a href="writesamplerfeedbackgrad-05ck.html#decl-clamp" class="code_param">clamp</a>)
    <span class='code_keyword'>where</span> <a href="writesamplerfeedbackgrad-05ck.html#typeparam-S" class="code_type">S</a> : <a href="../interfaces/itexelelement-016/index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a> == <a href="../types/0_shape2d-028/index.html" class="code_type">__Shape2D</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a> == 4
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a> == 0;

<span class="code_keyword">void</span> <a href="../types/0texture-01/index.html" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a>&gt;.<a href="writesamplerfeedbackgrad-05ck.html">WriteSamplerFeedbackGrad</a>&lt;<a href="writesamplerfeedbackgrad-05ck.html#typeparam-S" class="code_type">S</a>&gt;(
    <a href=".html" class="code_type">Texture2D</a>&lt;<a href="writesamplerfeedbackgrad-05ck.html#typeparam-S" class="code_type">S</a>&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-tex" class="code_param">tex</a>,
    <a href="../types/samplerstate-07/index.html" class="code_type">SamplerState</a> <a href="writesamplerfeedbackgrad-05ck.html#decl-samp" class="code_param">samp</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-location" class="code_param">location</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-ddx" class="code_param">ddx</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-ddy" class="code_param">ddy</a>)
    <span class='code_keyword'>where</span> <a href="writesamplerfeedbackgrad-05ck.html#typeparam-S" class="code_type">S</a> : <a href="../interfaces/itexelelement-016/index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a> == <a href="../types/0_shape2d-028/index.html" class="code_type">__Shape2D</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a> == 4
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a> == 0;

<span class="code_keyword">void</span> <a href="../types/0texture-01/index.html" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a>&gt;.<a href="writesamplerfeedbackgrad-05ck.html">WriteSamplerFeedbackGrad</a>&lt;<a href="writesamplerfeedbackgrad-05ck.html#typeparam-S" class="code_type">S</a>&gt;(
    <a href=".html" class="code_type">Texture2DArray</a>&lt;<a href="writesamplerfeedbackgrad-05ck.html#typeparam-S" class="code_type">S</a>&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-texArray" class="code_param">texArray</a>,
    <a href="../types/samplerstate-07/index.html" class="code_type">SamplerState</a> <a href="writesamplerfeedbackgrad-05ck.html#decl-samp" class="code_param">samp</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-location" class="code_param">location</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-ddx" class="code_param">ddx</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-ddy" class="code_param">ddy</a>,
    <span class="code_keyword">float</span> <a href="writesamplerfeedbackgrad-05ck.html#decl-clamp" class="code_param">clamp</a>)
    <span class='code_keyword'>where</span> <a href="writesamplerfeedbackgrad-05ck.html#typeparam-S" class="code_type">S</a> : <a href="../interfaces/itexelelement-016/index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a> : __BuiltinSamplerFeedbackType
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a> == <a href="../types/0_shape2d-028/index.html" class="code_type">__Shape2D</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a> == 1
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a> == 4
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a> == 0;

<span class="code_keyword">void</span> <a href="../types/0texture-01/index.html" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a>&gt;.<a href="writesamplerfeedbackgrad-05ck.html">WriteSamplerFeedbackGrad</a>&lt;<a href="writesamplerfeedbackgrad-05ck.html#typeparam-S" class="code_type">S</a>&gt;(
    <a href=".html" class="code_type">Texture2DArray</a>&lt;<a href="writesamplerfeedbackgrad-05ck.html#typeparam-S" class="code_type">S</a>&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-texArray" class="code_param">texArray</a>,
    <a href="../types/samplerstate-07/index.html" class="code_type">SamplerState</a> <a href="writesamplerfeedbackgrad-05ck.html#decl-samp" class="code_param">samp</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-location" class="code_param">location</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-ddx" class="code_param">ddx</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="writesamplerfeedbackgrad-05ck.html#decl-ddy" class="code_param">ddy</a>)
    <span class='code_keyword'>where</span> <a href="writesamplerfeedbackgrad-05ck.html#typeparam-S" class="code_type">S</a> : <a href="../interfaces/itexelelement-016/index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a> : __BuiltinSamplerFeedbackType
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a> == <a href="../types/0_shape2d-028/index.html" class="code_type">__Shape2D</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a> == 1
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a> == 4
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a> == 0;

</pre>

## Generic Parameters

####  <a id="typeparam-S"></a>S: [ITexelElement](../interfaces/itexelelement-016/index.html)

## Parameters

####  <a id="decl-tex"></a>tex  : [Texture2D](.html)\<S\>
####  <a id="decl-samp"></a>samp  : [SamplerState](../types/samplerstate-07/index.html)
####  <a id="decl-location"></a>location  : [vector](../types/vector/index.html)\<float, 2\>
####  <a id="decl-ddx"></a>ddx  : [vector](../types/vector/index.html)\<float, 2\>
####  <a id="decl-ddy"></a>ddy  : [vector](../types/vector/index.html)\<float, 2\>
####  <a id="decl-clamp"></a>clamp  : float
####  <a id="decl-texArray"></a>texArray  : [Texture2DArray](.html)\<S\>
####  <a id="decl-location"></a>location  : [vector](../types/vector/index.html)\<float, 3\>
####  <a id="decl-ddx"></a>ddx  : [vector](../types/vector/index.html)\<float, 3\>
####  <a id="decl-ddy"></a>ddy  : [vector](../types/vector/index.html)\<float, 3\>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### cpp
Available in all stages.



