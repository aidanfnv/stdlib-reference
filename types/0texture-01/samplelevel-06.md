---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.SampleLevel

## Description





## Signature 

<pre>
/// Requires Capability Set 1:
<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="samplelevel-06">SampleLevel</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplelevel-06#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplelevel-06#decl-level" class="code_param">level</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 2:
<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="samplelevel-06">SampleLevel</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplelevel-06#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplelevel-06#decl-level" class="code_param">level</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="samplelevel-06#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 3:
<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="samplelevel-06">SampleLevel</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplelevel-06#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplelevel-06#decl-level" class="code_param">level</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="samplelevel-06#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="samplelevel-06#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 1:
<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="samplelevel-06">SampleLevel</a>(
    <a href="../types/samplerstate-07/index" class="code_type">SamplerState</a> <a href="samplelevel-06#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplelevel-06#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplelevel-06#decl-level" class="code_param">level</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 2:
<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="samplelevel-06">SampleLevel</a>(
    <a href="../types/samplerstate-07/index" class="code_type">SamplerState</a> <a href="samplelevel-06#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplelevel-06#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplelevel-06#decl-level" class="code_param">level</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="samplelevel-06#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 3:
<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="samplelevel-06">SampleLevel</a>(
    <a href="../types/samplerstate-07/index" class="code_type">SamplerState</a> <a href="samplelevel-06#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="samplelevel-06#decl-location" class="code_param">location</a>,
    <span class="code_keyword">float</span> <a href="samplelevel-06#decl-level" class="code_param">level</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="samplelevel-06#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="samplelevel-06#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

####  <a id="decl-location"></a>location  : [vector](../types/vector/index)\<float, isArray + Shape\.dimensions\>
####  <a id="decl-level"></a>level  : float
####  <a id="decl-offset"></a>offset  : [vector](../types/vector/index)\<int, Shape\.planeDimensions\>
####  <a id="decl-status"></a>status  : uint
####  <a id="decl-s"></a>s  : [SamplerState](../types/samplerstate-07/index)

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
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

#### wgsl
Available in all stages.

#### spirv
Available in all stages.


### Capability Set 3

Defined for the following targets:

#### hlsl
Available in all stages.

#### spirv
Available in all stages.

Requires capabilities: `SPV_KHR_non_semantic_info`, `SPV_GOOGLE_user_type`, `spvDerivativeControl`, `spvImageQuery`, `spvImageGatherExtended`, `spvSparseResidency`, `spvMinLod`, `spvFragmentFullyCoveredEXT`.


