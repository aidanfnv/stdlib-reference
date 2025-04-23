---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.WriteSamplerFeedbackGrad

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="writesamplerfeedbackgrad-05ck.md">WriteSamplerFeedbackGrad</a>&lt;<a href="writesamplerfeedbackgrad-05ck.md#typeparam-S" class="code_type">S</a>&gt;(
    <a href="../texture2d-08.md" class="code_type">Texture2D</a>&lt;<a href="writesamplerfeedbackgrad-05ck.md#typeparam-S" class="code_type">S</a>&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-tex" class="code_param">tex</a>,
    <a href="../samplerstate-07/index.md" class="code_type">SamplerState</a> <a href="writesamplerfeedbackgrad-05ck.md#decl-samp" class="code_param">samp</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-ddx" class="code_param">ddx</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-ddy" class="code_param">ddy</a>,
    <span class="code_keyword">float</span> <a href="writesamplerfeedbackgrad-05ck.md#decl-clamp" class="code_param">clamp</a>)
    <span class='code_keyword'>where</span> <a href="writesamplerfeedbackgrad-05ck.md#typeparam-S" class="code_type">S</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> == <a href="../0_shape2d-028/index.md" class="code_type">__Shape2D</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-isShadow" class="code_var">isShadow</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-format" class="code_var">format</a> == 0;

<span class="code_keyword">void</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="writesamplerfeedbackgrad-05ck.md">WriteSamplerFeedbackGrad</a>&lt;<a href="writesamplerfeedbackgrad-05ck.md#typeparam-S" class="code_type">S</a>&gt;(
    <a href="../texture2d-08.md" class="code_type">Texture2D</a>&lt;<a href="writesamplerfeedbackgrad-05ck.md#typeparam-S" class="code_type">S</a>&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-tex" class="code_param">tex</a>,
    <a href="../samplerstate-07/index.md" class="code_type">SamplerState</a> <a href="writesamplerfeedbackgrad-05ck.md#decl-samp" class="code_param">samp</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-ddx" class="code_param">ddx</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 2&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-ddy" class="code_param">ddy</a>)
    <span class='code_keyword'>where</span> <a href="writesamplerfeedbackgrad-05ck.md#typeparam-S" class="code_type">S</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> == <a href="../0_shape2d-028/index.md" class="code_type">__Shape2D</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-isShadow" class="code_var">isShadow</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-format" class="code_var">format</a> == 0;

<span class="code_keyword">void</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="writesamplerfeedbackgrad-05ck.md">WriteSamplerFeedbackGrad</a>&lt;<a href="writesamplerfeedbackgrad-05ck.md#typeparam-S" class="code_type">S</a>&gt;(
    <a href="../texture2darray-089.md" class="code_type">Texture2DArray</a>&lt;<a href="writesamplerfeedbackgrad-05ck.md#typeparam-S" class="code_type">S</a>&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-texArray" class="code_param">texArray</a>,
    <a href="../samplerstate-07/index.md" class="code_type">SamplerState</a> <a href="writesamplerfeedbackgrad-05ck.md#decl-samp" class="code_param">samp</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-ddx" class="code_param">ddx</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-ddy" class="code_param">ddy</a>,
    <span class="code_keyword">float</span> <a href="writesamplerfeedbackgrad-05ck.md#decl-clamp" class="code_param">clamp</a>)
    <span class='code_keyword'>where</span> <a href="writesamplerfeedbackgrad-05ck.md#typeparam-S" class="code_type">S</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : __BuiltinSamplerFeedbackType
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> == <a href="../0_shape2d-028/index.md" class="code_type">__Shape2D</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-isArray" class="code_var">isArray</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-isShadow" class="code_var">isShadow</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-format" class="code_var">format</a> == 0;

<span class="code_keyword">void</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="writesamplerfeedbackgrad-05ck.md">WriteSamplerFeedbackGrad</a>&lt;<a href="writesamplerfeedbackgrad-05ck.md#typeparam-S" class="code_type">S</a>&gt;(
    <a href="../texture2darray-089.md" class="code_type">Texture2DArray</a>&lt;<a href="writesamplerfeedbackgrad-05ck.md#typeparam-S" class="code_type">S</a>&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-texArray" class="code_param">texArray</a>,
    <a href="../samplerstate-07/index.md" class="code_type">SamplerState</a> <a href="writesamplerfeedbackgrad-05ck.md#decl-samp" class="code_param">samp</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-ddx" class="code_param">ddx</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt; <a href="writesamplerfeedbackgrad-05ck.md#decl-ddy" class="code_param">ddy</a>)
    <span class='code_keyword'>where</span> <a href="writesamplerfeedbackgrad-05ck.md#typeparam-S" class="code_type">S</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : __BuiltinSamplerFeedbackType
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> == <a href="../0_shape2d-028/index.md" class="code_type">__Shape2D</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-isArray" class="code_var">isArray</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-isShadow" class="code_var">isShadow</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-format" class="code_var">format</a> == 0;

</pre>

## Generic Parameters

####  <a id="typeparam-S"></a>S: [ITexelElement](../../interfaces/itexelelement-016/index.md)

## Parameters

####  <a id="decl-tex"></a>tex  : [Texture2D](../texture2d-08.md)\<S\>
####  <a id="decl-samp"></a>samp  : [SamplerState](../samplerstate-07/index.md)
####  <a id="decl-location"></a>location  : [vector](../vector/index.md)\<float, 2\>
####  <a id="decl-ddx"></a>ddx  : [vector](../vector/index.md)\<float, 2\>
####  <a id="decl-ddy"></a>ddy  : [vector](../vector/index.md)\<float, 2\>
####  <a id="decl-clamp"></a>clamp  : float
####  <a id="decl-texArray"></a>texArray  : [Texture2DArray](../texture2darray-089.md)\<S\>
####  <a id="decl-location"></a>location  : [vector](../vector/index.md)\<float, 3\>
####  <a id="decl-ddx"></a>ddx  : [vector](../vector/index.md)\<float, 3\>
####  <a id="decl-ddy"></a>ddy  : [vector](../vector/index.md)\<float, 3\>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### cpp
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
