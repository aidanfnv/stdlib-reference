---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.Sample

## Description

Samples the texture at the given location.




## Signature 

<pre>
/// Requires Capability Set 1:
<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="sample-0">Sample</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0#decl-location" class="code_param">location</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 2:
<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="sample-0">Sample</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0#decl-location" class="code_param">location</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="sample-0#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 3:
<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="sample-0">Sample</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0#decl-location" class="code_param">location</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="sample-0#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">float</span> <a href="sample-0#decl-clamp" class="code_param">clamp</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="sample-0">Sample</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0#decl-location" class="code_param">location</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="sample-0#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">float</span> <a href="sample-0#decl-clamp" class="code_param">clamp</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="sample-0#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 1:
<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="sample-0">Sample</a>(
    <a href="../types/samplerstate-07/index" class="code_type">SamplerState</a> <a href="sample-0#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0#decl-location" class="code_param">location</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 2:
<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="sample-0">Sample</a>(
    <a href="../types/samplerstate-07/index" class="code_type">SamplerState</a> <a href="sample-0#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0#decl-location" class="code_param">location</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="sample-0#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 4:
<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="sample-0">Sample</a>(
    <a href="../types/samplerstate-07/index" class="code_type">SamplerState</a> <a href="sample-0#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0#decl-location" class="code_param">location</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="sample-0#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">float</span> <a href="sample-0#decl-clamp" class="code_param">clamp</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="sample-0">Sample</a>(
    <a href="../types/samplerstate-07/index" class="code_type">SamplerState</a> <a href="sample-0#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0#decl-location" class="code_param">location</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="sample-0#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">float</span> <a href="sample-0#decl-clamp" class="code_param">clamp</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="sample-0#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

####  <a id="decl-location"></a>location  : [vector](../types/vector/index)\<float, isArray + Shape\.dimensions\>
The location to sample the texture at.

####  <a id="decl-offset"></a>offset  : [vector](../types/vector/index)\<int, Shape\.planeDimensions\>
Texel offset to apply.

####  <a id="decl-clamp"></a>clamp  : float
The max level of detail to use.

####  <a id="decl-status"></a>status  : uint
\[out\] The result status of the operation.
This parameter is currently only used when targeting HLSL.
For other targets, the result status is always 0.

####  <a id="decl-s"></a>s  : [SamplerState](../types/samplerstate-07/index)
The <span class='code'><a href="../types/samplerstate-07/index" class="code_type">SamplerState</a></span> to use for the sampling operation. This parameter is omitted when <span class='code'>this</span> is a combined texture sampler type (<span class='code'><a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>==0</span>).


## Return value
The sampled texture value.

## Remarks

The <span class='code'><a href="sample-0">Sample</a></span> function is defined for all read-only texture types, including
<span class='code'><a href="" class="code_type">Texture1D</a></span>, <span class='code'><a href="" class="code_type">Texture2D</a></span>, <span class='code'><a href="" class="code_type">Texture3D</a></span>, <span class='code'><a href="" class="code_type">TextureCube</a></span>,
<span class='code'><a href="" class="code_type">Texture1DArray</a></span>, <span class='code'><a href="" class="code_type">Texture2DArray</a></span> and <span class='code'><a href="" class="code_type">TextureCubeArray</a></span>.

The function is not available for read-write texture types.

For HLSL/D3D targets, the texture element type must be a scalar or vector of float or half types.


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

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### metal
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvSparseResidency`.

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



## See Also
<span class='code'><a href="">SampleBias</a></span>, <span class='code'><a href="">SampleLevel</a></span>, <span class='code'><a href="">SampleGrad</a></span>, <span class='code'><a href="">SampleCmp</a></span>, <span class='code'><a href="">SampleCmpLevelZero</a></span>, <span class='code'><a href="">SampleCmpLevel</a></span>.

