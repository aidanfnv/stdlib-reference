---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.InterlockedAddF32

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="interlockedaddf32-0be">InterlockedAddF32</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="interlockedaddf32-0be#decl-coord" class="code_param">coord</a>,
    <span class="code_keyword">float</span> <a href="interlockedaddf32-0be#decl-value" class="code_param">value</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">float</span> <a href="interlockedaddf32-0be#decl-originalValue" class="code_param">originalValue</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> == <span class="code_keyword">float</span>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape1d2d3d-023agik/index" class="code_type">__ITextureShape1D2D3D</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 1
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

<span class="code_keyword">float</span> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="interlockedaddf32-0be">InterlockedAddF32</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="interlockedaddf32-0be#decl-coord" class="code_param">coord</a>,
    <span class="code_keyword">float</span> <a href="interlockedaddf32-0be#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> == <span class="code_keyword">float</span>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape1d2d3d-023agik/index" class="code_type">__ITextureShape1D2D3D</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 1
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

####  <a id="decl-coord"></a>coord  : [vector](../types/vector/index)\<uint, Shape\.dimensions\>
####  <a id="decl-value"></a>value  : float
####  <a id="decl-originalValue"></a>originalValue  : float

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

Requires capability: `hlsl_nvapi`.
#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capabilities: `spvAtomicFloat32AddEXT`, `spvAtomicFloat32MinMaxEXT`.


