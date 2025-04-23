---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.Sample

## Description

Samples the texture at the given location.




## Signature 

<pre>
/// Requires Capability Set 1:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="sample-0.md">Sample</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0.md#decl-location" class="code_param">location</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 2:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="sample-0.md">Sample</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="sample-0.md#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 3:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="sample-0.md">Sample</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="sample-0.md#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">float</span> <a href="sample-0.md#decl-clamp" class="code_param">clamp</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 1;

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="sample-0.md">Sample</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="sample-0.md#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">float</span> <a href="sample-0.md#decl-clamp" class="code_param">clamp</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="sample-0.md#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 1:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="sample-0.md">Sample</a>(
    <a href="../samplerstate-07/index.md" class="code_type">SamplerState</a> <a href="sample-0.md#decl-s" class="code_param">s</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0.md#decl-location" class="code_param">location</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 2:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="sample-0.md">Sample</a>(
    <a href="../samplerstate-07/index.md" class="code_type">SamplerState</a> <a href="sample-0.md#decl-s" class="code_param">s</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="sample-0.md#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 4:
<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="sample-0.md">Sample</a>(
    <a href="../samplerstate-07/index.md" class="code_type">SamplerState</a> <a href="sample-0.md#decl-s" class="code_param">s</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="sample-0.md#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">float</span> <a href="sample-0.md#decl-clamp" class="code_param">clamp</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

<a href="index.md#typeparam-T" class="code_type">T</a> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="sample-0.md">Sample</a>(
    <a href="../samplerstate-07/index.md" class="code_type">SamplerState</a> <a href="sample-0.md#decl-s" class="code_param">s</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="sample-0.md#decl-location" class="code_param">location</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="sample-0.md#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">float</span> <a href="sample-0.md#decl-clamp" class="code_param">clamp</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="sample-0.md#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

####  <a id="decl-location"></a>location  : [vector](../vector/index.md)\<float, isArray + Shape\.dimensions\>
The location to sample the texture at.

####  <a id="decl-offset"></a>offset  : [vector](../vector/index.md)\<int, Shape\.planeDimensions\>
Texel offset to apply.

####  <a id="decl-clamp"></a>clamp  : float
The max level of detail to use.

####  <a id="decl-status"></a>status  : uint
\[out\] The result status of the operation.
This parameter is currently only used when targeting HLSL.
For other targets, the result status is always 0.

####  <a id="decl-s"></a>s  : [SamplerState](../samplerstate-07/index.md)
The <span class='code'><a href="../samplerstate-07/index.md" class="code_type">SamplerState</a></span> to use for the sampling operation. This parameter is omitted when <span class='code'>this</span> is a combined texture sampler type (<span class='code'><a href="index.md#decl-isCombined" class="code_var">isCombined</a>==0</span>).


## Return value
The sampled texture value.

## Remarks

The <span class='code'><a href="sample-0.md">Sample</a></span> function is defined for all read-only texture types, including
<span class='code'><a href="../texture1d-08.md" class="code_type">Texture1D</a></span>, <span class='code'><a href="../texture2d-08.md" class="code_type">Texture2D</a></span>, <span class='code'><a href="../texture3d-08.md" class="code_type">Texture3D</a></span>, <span class='code'><a href="../texturecube-07.md" class="code_type">TextureCube</a></span>,
<span class='code'><a href="../texture1darray-089.md" class="code_type">Texture1DArray</a></span>, <span class='code'><a href="../texture2darray-089.md" class="code_type">Texture2DArray</a></span> and <span class='code'><a href="../texturecubearray-07b.md" class="code_type">TextureCubeArray</a></span>.

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
<span class='code'><a href="samplebias-06.md">SampleBias</a></span>, <span class='code'><a href="samplelevel-06.md">SampleLevel</a></span>, <span class='code'><a href="samplegrad-06.md">SampleGrad</a></span>, <span class='code'><a href="samplecmp-06.md">SampleCmp</a></span>, <span class='code'><a href="samplecmplevelzero-069e.md">SampleCmpLevelZero</a></span>, <span class='code'><a href="samplecmplevel-069.md">SampleCmpLevel</a></span>.


<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      const href = link.getAttribute('href');
      if (href && href.includes('.md')) {
        // This regex will handle .md links with or without fragment identifiers or query parameters
        link.href = link.href.replace(/(.+)\.md(#[^?]*)?(\?.*)?$/, '$1.html$2$3');
      }
    });
  });
}
</script>
