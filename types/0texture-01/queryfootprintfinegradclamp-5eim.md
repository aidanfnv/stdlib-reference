---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.queryFootprintFineGradClamp

## Description

Query the footprint that would be accessed by a texture sampling operation.

This operation queries the footprint that would be accessed
by a comparable call to:

t.SampleGradClamp(sampler, coords, dx, dy, lodClamp);




## Signature 

<pre>
<a href="../types/texturefootprint-07/index.html" class="code_type">TextureFootprint</a>&lt;<a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="../types/0texture-01/index.html" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index.html#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index.html#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index.html#decl-format" class="code_var">format</a>&gt;.<a href="queryfootprintfinegradclamp-5eim.html">queryFootprintFineGradClamp</a>(
    <span class="code_keyword">uint</span> <a href="queryfootprintfinegradclamp-5eim.html#decl-granularity" class="code_param">granularity</a>,
    <a href="../types/samplerstate-07/index.html" class="code_type">SamplerState</a> <a href="queryfootprintfinegradclamp-5eim.html#decl-sampler" class="code_param">sampler</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="queryfootprintfinegradclamp-5eim.html#decl-coords" class="code_param">coords</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="queryfootprintfinegradclamp-5eim.html#decl-dx" class="code_param">dx</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="queryfootprintfinegradclamp-5eim.html#decl-dy" class="code_param">dy</a>,
    <span class="code_keyword">float</span> <a href="queryfootprintfinegradclamp-5eim.html#decl-lodClamp" class="code_param">lodClamp</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index.html" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index.html" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index.html#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

####  <a id="decl-granularity"></a>granularity  : uint
####  <a id="decl-sampler"></a>sampler  : [SamplerState](../types/samplerstate-07/index.html)
####  <a id="decl-coords"></a>coords  : [vector](../types/vector/index.html)\<float, Shape\.dimensions\>
####  <a id="decl-dx"></a>dx  : [vector](../types/vector/index.html)\<float, Shape\.dimensions\>
####  <a id="decl-dy"></a>dy  : [vector](../types/vector/index.html)\<float, Shape\.dimensions\>
####  <a id="decl-lodClamp"></a>lodClamp  : float

