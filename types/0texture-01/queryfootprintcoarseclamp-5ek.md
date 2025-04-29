---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.queryFootprintCoarseClamp

## Description

Query the footprint that would be accessed by a texture sampling operation.

This operation queries the footprint that would be accessed
by a comparable call to:

t.SampleClamp(sampler, coords, lodClamp);




## Signature 

<pre>
<a href="../types/texturefootprint-07/index" class="code_type">TextureFootprint</a>&lt;<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="queryfootprintcoarseclamp-5ek">queryFootprintCoarseClamp</a>(
    <span class="code_keyword">uint</span> <a href="queryfootprintcoarseclamp-5ek#decl-granularity" class="code_param">granularity</a>,
    <a href="../types/samplerstate-07/index" class="code_type">SamplerState</a> <a href="queryfootprintcoarseclamp-5ek#decl-sampler" class="code_param">sampler</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="queryfootprintcoarseclamp-5ek#decl-coords" class="code_param">coords</a>,
    <span class="code_keyword">float</span> <a href="queryfootprintcoarseclamp-5ek#decl-lodClamp" class="code_param">lodClamp</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

####  <a id="decl-granularity"></a>granularity  : uint
####  <a id="decl-sampler"></a>sampler  : [SamplerState](../types/samplerstate-07/index)
####  <a id="decl-coords"></a>coords  : [vector](../types/vector/index)\<float, Shape\.dimensions\>
####  <a id="decl-lodClamp"></a>lodClamp  : float

