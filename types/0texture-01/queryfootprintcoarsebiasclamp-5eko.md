---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.queryFootprintCoarseBiasClamp

## Description

Query the footprint that would be accessed by a texture sampling operation.

This operation queries the footprint that would be accessed
by a comparable call to:

t.SampleBiasClamp(sampler, coords, lodBias, lodClamp);




## Signature 

<pre>
<a href="/stdlib-reference/types/texturefootprint-07/index" class="code_type">TextureFootprint</a>&lt;<a href="/stdlib-reference/types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="/stdlib-reference/types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="/stdlib-reference/types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="/stdlib-reference/types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="/stdlib-reference/types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="/stdlib-reference/types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="/stdlib-reference/types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="/stdlib-reference/types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="/stdlib-reference/types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="/stdlib-reference/types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="/stdlib-reference/types/0texture-01/queryfootprintcoarsebiasclamp-5eko">queryFootprintCoarseBiasClamp</a>(
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/0texture-01/queryfootprintcoarsebiasclamp-5eko#decl-granularity" class="code_param">granularity</a>,
    <a href="/stdlib-reference/types/samplerstate-07/index" class="code_type">SamplerState</a> <a href="/stdlib-reference/types/0texture-01/queryfootprintcoarsebiasclamp-5eko#decl-sampler" class="code_param">sampler</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="/stdlib-reference/types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="/stdlib-reference/types/0texture-01/queryfootprintcoarsebiasclamp-5eko#decl-coords" class="code_param">coords</a>,
    <span class="code_keyword">float</span> <a href="/stdlib-reference/types/0texture-01/queryfootprintcoarsebiasclamp-5eko#decl-lodBias" class="code_param">lodBias</a>,
    <span class="code_keyword">float</span> <a href="/stdlib-reference/types/0texture-01/queryfootprintcoarsebiasclamp-5eko#decl-lodClamp" class="code_param">lodClamp</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="/stdlib-reference/interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/0texture-01/index#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

#### granularity  : uint {#decl-granularity}
#### sampler  : [SamplerState](/stdlib-reference/types/samplerstate-07/index) {#decl-sampler}
#### coords  : [vector](/stdlib-reference/types/vector/index)\<float, Shape\.dimensions\> {#decl-coords}
#### lodBias  : float {#decl-lodBias}
#### lodClamp  : float {#decl-lodClamp}

