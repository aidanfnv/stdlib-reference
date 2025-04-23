---
layout: stdlib-reference
---

# struct \_Texture\<T, Shape, isArray:int, isMS:int, sampleCount:int, access:int, isShadow:int, isCombined:int, format:int\>

*Conditionally conforms to:* \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>

> #### Internal Feature
> The feature described in this page is marked as an internal implementation detail, and is not intended for use by end-users.
> Users are advised to avoid using this declaration directly, as it may be removed or changed in future releases.

## Description

A parameterized type that represents all flavors of texture types supported by the Slang language.
Please note that this type is not intended to be used directly in user code, and not all combinations
of the generic arguments are valid.
Instead, use the specific texture types such as <span class='code'><a href="../texture1d-08.md" class="code_type">Texture1D</a></span>, <span class='code'><a href="../texture2darray-089.md" class="code_type">Texture2DArray</a></span> and <span class='code'><a href="../sampler2d-08.md" class="code_type">Sampler2D</a></span> etc.
This documentation is provided for reference purposes only.


## Generic Parameters

####  <a id="typeparam-T"></a>T: [ITexelElement](../../interfaces/itexelelement-016/index.md)
The element type of the texture. Must be a scalar or vector type.

####  <a id="typeparam-Shape"></a>Shape: [\_\_ITextureShape](../../interfaces/0_itextureshape-023a/index.md)
The shape of the texture. Must be one of <span class='code'><a href="../0_shape1d-028/index.md" class="code_type">__Shape1D</a></span>, <span class='code'><a href="../0_shape2d-028/index.md" class="code_type">__Shape2D</a></span>, <span class='code'><a href="../0_shape3d-028/index.md" class="code_type">__Shape3D</a></span>, <span class='code'><a href="../0_shapecube-027/index.md" class="code_type">__ShapeCube</a></span> or <span class='code'><a href="../0_shapebuffer-027/index.md" class="code_type">__ShapeBuffer</a></span>.

####  <a id="decl-isArray"></a>isArray  : int
Indicates whether the texture is an array texture.

####  <a id="decl-isMS"></a>isMS  : int
Indicates whether the texture is a multisampled texture.

####  <a id="decl-sampleCount"></a>sampleCount  : int
The number of samples of a multisampled texture.

####  <a id="decl-access"></a>access  : int
The access mode of the texture. 0 for read-only, 1 for read-write, 2 for rasterizer-ordered, 3 for feedback.

####  <a id="decl-isShadow"></a>isShadow  : int
Indicates whether the texture is a shadow texture (for combined texture-sampler only).

####  <a id="decl-isCombined"></a>isCombined  : int
Indicates whether the texture is a combined texture-sampler.

####  <a id="decl-format"></a>format  : int
The storage format of the texture. Users should specify the format using an <span class='code'>[<a href="index.md#decl-format" class="code_var">format</a>(&quot;...&quot;)]</span> attribute instead.


## Fields

####  <a id="decl-kind"></a>[kind](kind.md) : [DescriptorKind](../descriptorkind-0a/index.md) =\.\.\.

## Methods

* [CalculateLevelOfDetail](calculatelevelofdetail-09eg.md)
* [CalculateLevelOfDetailUnclamped](calculatelevelofdetailunclamped-09egm.md)
* [Sample](sample-0.md)
* [SampleBias](samplebias-06.md)
* [SampleCmp](samplecmp-06.md)
* [SampleCmpLevelZero](samplecmplevelzero-069e.md)
* [SampleCmpLevel](samplecmplevel-069.md)
* [SampleGrad](samplegrad-06.md)
* [SampleLevel](samplelevel-06.md)
* [GetSamplePosition](getsampleposition-039.md)
* [Gather](gather-0.md)
* [GatherRed](gatherred-06.md)
* [GatherGreen](gathergreen-06.md)
* [GatherBlue](gatherblue-06.md)
* [GatherAlpha](gatheralpha-06.md)
* [GatherCmp](gathercmp-06.md)
* [GatherCmpRed](gathercmpred-069.md)
* [GatherCmpGreen](gathercmpgreen-069.md)
* [GatherCmpBlue](gathercmpblue-069.md)
* [GatherCmpAlpha](gathercmpalpha-069.md)
* [Store](store-0.md)
* [GetDimensions](getdimensions-03.md)
* [Load](load-0.md)
* [subscript](subscript.md)
* [WriteSamplerFeedbackLevel](writesamplerfeedbacklevel-05ck.md)
* [WriteSamplerFeedback](writesamplerfeedback-05c.md)
* [WriteSamplerFeedbackBias](writesamplerfeedbackbias-05ck.md)
* [WriteSamplerFeedbackGrad](writesamplerfeedbackgrad-05ck.md)
* [queryFootprintCoarse](queryfootprintcoarse-5e.md)
* [queryFootprintCoarseBias](queryfootprintcoarsebias-5ek.md)
* [queryFootprintCoarseClamp](queryfootprintcoarseclamp-5ek.md)
* [queryFootprintCoarseBiasClamp](queryfootprintcoarsebiasclamp-5eko.md)
* [queryFootprintCoarseLevel](queryfootprintcoarselevel-5ek.md)
* [queryFootprintCoarseGrad](queryfootprintcoarsegrad-5ek.md)
* [queryFootprintCoarseGradClamp](queryfootprintcoarsegradclamp-5eko.md)
* [queryFootprintFine](queryfootprintfine-5e.md)
* [queryFootprintFineBias](queryfootprintfinebias-5ei.md)
* [queryFootprintFineClamp](queryfootprintfineclamp-5ei.md)
* [queryFootprintFineBiasClamp](queryfootprintfinebiasclamp-5eim.md)
* [queryFootprintFineLevel](queryfootprintfinelevel-5ei.md)
* [queryFootprintFineGrad](queryfootprintfinegrad-5ei.md)
* [queryFootprintFineGradClamp](queryfootprintfinegradclamp-5eim.md)
* [InterlockedAddF32](interlockedaddf32-0be.md)
* [init](init.md)

## Conditional Conformances

### Conformance to \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>
`_Texture<T, Shape, isArray:int, isMS:int, sampleCount:int, access:int, isShadow:int, isCombined:int, format:int>` additionally conforms to `\_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>` when the following conditions are met:

  * [T](index.md#typeparam-T) : [ITexelElement](../../interfaces/itexelelement-016/index.md)
  * [Shape](index.md#typeparam-Shape) : [\_\_ITextureShape](../../interfaces/0_itextureshape-023a/index.md)
## Remarks


HLSL texture types are implemented as typealiases to the builtin <span class='code'><a href="index.md" class="code_type">_Texture</a></span> type. Users
are advised to use the HLSL-specific texture types instead of <span class='code'><a href="index.md" class="code_type">_Texture</a></span> directly.

For read-write textures, Slang will automatically infer <span class='code'><a href="index.md#decl-format" class="code_var">format</a></span> from <span class='code'><a href="index.md#typeparam-T" class="code_type">T</a></span>.
To explicitly specify texel storage formats for read-write textures,
use the <span class='code'>[<a href="index.md#decl-format" class="code_var">format</a>(&quot;formatString&quot;)]</span> attribute on the texture parameter declaration.
Allowed <span class='code'>formatString</span> values are:

|id | Format string        | Meaning           |
|:--|:---------------------|:------------------|
|1  |<span class='code'>&quot;rgba32f&quot;</span>           | 4 channel 32-bit floating point texture |
|2  |<span class='code'>&quot;rgba16f&quot;</span>           | 4 channel 16-bit floating point texture |
|3  |<span class='code'>&quot;rg32f&quot;</span>             | 2 channel 32-bit floating point texture |
|4  |<span class='code'>&quot;rg16f&quot;</span>             | 2 channel 16-bit floating point texture |
|5  |<span class='code'>&quot;r11f_g11f_b10f&quot;</span>    | 3 channel 11/11/10-bit floating point texture |
|6  |<span class='code'>&quot;r32f&quot;</span>              | 1 channel 32-bit floating point texture |
|7  |<span class='code'>&quot;r16f&quot;</span>              | 1 channel 16-bit floating point texture |
|8  |<span class='code'>&quot;rgba16&quot;</span>            | 4 channel 16-bit normalized unsigned integer texture |
|9  |<span class='code'>&quot;rgb10_a2&quot;</span>          | 4 channel 10/10/10/2-bit signed integer texture |
|10 |<span class='code'>&quot;rgba8&quot;</span>             | 4 channel 8-bit normalized unsigned integer texture |
|11 |<span class='code'>&quot;rg16&quot;</span>              | 2 channel 16-bit normalized unsigned integer texture |
|12 |<span class='code'>&quot;rg8&quot;</span>               | 2 channel 8-bit normalized unsigned integer texture |
|13 |<span class='code'>&quot;r16&quot;</span>               | 1 channel 16-bit normalized unsigned integer texture |
|14 |<span class='code'>&quot;r8&quot;</span>                | 1 channel 8-bit normalized unsigned integer texture |
|15 |<span class='code'>&quot;rgba16_snorm&quot;</span>      | 4 channel 16-bit normalized signed integer texture |
|16 |<span class='code'>&quot;rgba8_snorm&quot;</span>       | 4 channel 8-bit normalized signed integer texture |
|17 |<span class='code'>&quot;rg16_snorm&quot;</span>        | 2 channel 16-bit normalized signed integer texture |
|18 |<span class='code'>&quot;rg8_snorm&quot;</span>         | 2 channel 8-bit normalized signed integer texture |
|19 |<span class='code'>&quot;r16_snorm&quot;</span>         | 1 channel 16-bit normalized signed integer texture |
|20 |<span class='code'>&quot;r8_snorm&quot;</span>          | 1 channel 8-bit normalized signed integer texture |
|21 |<span class='code'>&quot;rgba32i&quot;</span>           | 4 channel 32-bit signed integer texture |
|22 |<span class='code'>&quot;rgba16i&quot;</span>           | 4 channel 16-bit signed integer texture |
|23 |<span class='code'>&quot;rgba8i&quot;</span>            | 4 channel 8-bit signed integer texture |
|24 |<span class='code'>&quot;rg32i&quot;</span>             | 2 channel 32-bit signed integer texture |
|25 |<span class='code'>&quot;rg16i&quot;</span>             | 2 channel 16-bit signed integer texture |
|26 |<span class='code'>&quot;rg8i&quot;</span>              | 2 channel 8-bit signed integer texture |
|27 |<span class='code'>&quot;r32i&quot;</span>              | 1 channel 32-bit signed integer texture |
|28 |<span class='code'>&quot;r16i&quot;</span>              | 1 channel 16-bit signed integer texture |
|29 |<span class='code'>&quot;r8i&quot;</span>               | 1 channel 8-bit signed integer texture |
|30 |<span class='code'>&quot;rgba32ui&quot;</span>          | 4 channel 32-bit unsigned integer texture |
|31 |<span class='code'>&quot;rgba16ui&quot;</span>          | 4 channel 16-bit unsigned integer texture |
|32 |<span class='code'>&quot;rgb10_a2ui&quot;</span>        | 4 channel 10/10/10/2-bit unsigned integer texture |
|33 |<span class='code'>&quot;rgba8ui&quot;</span>           | 4 channel 8-bit unsigned integer texture |
|34 |<span class='code'>&quot;rg32ui&quot;</span>            | 2 channel 32-bit unsigned integer texture |
|35 |<span class='code'>&quot;rg16ui&quot;</span>            | 2 channel 16-bit unsigned integer texture |
|36 |<span class='code'>&quot;rg8ui&quot;</span>             | 2 channel 8-bit unsigned integer texture |
|37 |<span class='code'>&quot;r32ui&quot;</span>             | 1 channel 32-bit unsigned integer texture |
|38 |<span class='code'>&quot;r16ui&quot;</span>             | 1 channel 16-bit unsigned integer texture |
|39 |<span class='code'>&quot;r8ui&quot;</span>              | 1 channel 8-bit unsigned integer texture |
|40 |<span class='code'>&quot;r64ui&quot;</span>             | 1 channel 64-bit unsigned integer texture |
|41 |<span class='code'>&quot;r64i&quot;</span>              | 1 channel 64-bit signed integer texture |

When targeting Vulkan, a combined-texture-sampler type (<span class='code'><a href="index.md#decl-isCombined" class="code_var">isCombined</a>==1</span>) translates to a <span class='code'>OpTypeSampledImage</span> type in SPIR-V.
For other targets, the combined-texture-sampler type is translated to a pair of a <span class='code'>Texture</span> and <span class='code'><a href="../samplerstate-07/index.md" class="code_type">SamplerState</a></span>.
<span class='code'><a href="index.md#decl-isShadow" class="code_var">isShadow</a></span> is only applicable to combined-texture-sampler types and must be <span class='code'>0</span> for non-combined texture types.

## See also

<span class='code'><a href="../texture1d-08.md" class="code_type">Texture1D</a></span>, <span class='code'><a href="../texture2d-08.md" class="code_type">Texture2D</a></span>, <span class='code'><a href="../texture3d-08.md" class="code_type">Texture3D</a></span>, <span class='code'><a href="../texturecube-07.md" class="code_type">TextureCube</a></span>, <span class='code'><a href="../texture1darray-089.md" class="code_type">Texture1DArray</a></span>,
<span class='code'><a href="../texture2darray-089.md" class="code_type">Texture2DArray</a></span>, <span class='code'><a href="../texturecubearray-07b.md" class="code_type">TextureCubeArray</a></span>, <span class='code'><a href="../sampler1d-08.md" class="code_type">Sampler1D</a></span>, <span class='code'><a href="../sampler2d-08.md" class="code_type">Sampler2D</a></span>, <span class='code'><a href="../sampler3d-08.md" class="code_type">Sampler3D</a></span>, <span class='code'><a href="../samplercube-07.md" class="code_type">SamplerCube</a></span>, <span class='code'><a href="../sampler1darray-089.md" class="code_type">Sampler1DArray</a></span>, <span class='code'><a href="../sampler2darray-089.md" class="code_type">Sampler2DArray</a></span>, <span class='code'><a href="../samplercubearray-07b.md" class="code_type">SamplerCubeArray</a></span>,
<span class='code'><a href="../texture2dms-089a.md" class="code_type">Texture2DMS</a></span>, <span class='code'><a href="../texture2dmsarray-089ab.md" class="code_type">Texture2DMSArray</a></span>, <span class='code'><a href="../rwtexture1d-012a.md" class="code_type">RWTexture1D</a></span>, <span class='code'><a href="../rwtexture2d-012a.md" class="code_type">RWTexture2D</a></span>, <span class='code'><a href="../rwtexture3d-012a.md" class="code_type">RWTexture3D</a></span>, <span class='code'><a href="../rwtexture1darray-012ab.md" class="code_type">RWTexture1DArray</a></span>, <span class='code'><a href="../rwtexture2darray-012ab.md" class="code_type">RWTexture2DArray</a></span>,
<span class='code'><a href="../rwtexture2dms-012abc.md" class="code_type">RWTexture2DMS</a></span>, <span class='code'><a href="../rwtexture2dmsarray-012abcd.md" class="code_type">RWTexture2DMSArray</a></span>, <span class='code'><a href="../buffer-0.md" class="code_type">Buffer</a></span>, <span class='code'><a href="../rwbuffer-012.md" class="code_type">RWBuffer</a></span>, <span class='code'><a href="../feedbacktexture2d-08g.md" class="code_type">FeedbackTexture2D</a></span>, <span class='code'><a href="../feedbacktexture2darray-08gh.md" class="code_type">FeedbackTexture2DArray</a></span>.


```{toctree}
:titlesonly:
:hidden:

CalculateLevelOfDetail <../types/0texture-01/calculatelevelofdetail-09eg>
CalculateLevelOfDetailUnclamped <../types/0texture-01/calculatelevelofdetailunclamped-09egm>
Coords <../types/0texture-01/coords-0>
Footprint <../types/0texture-01/footprint-0>
FootprintGranularity <../types/0texture-01/footprintgranularity-09>
Gather <../types/0texture-01/gather-0>
GatherAlpha <../types/0texture-01/gatheralpha-06>
GatherBlue <../types/0texture-01/gatherblue-06>
GatherCmp <../types/0texture-01/gathercmp-06>
GatherCmpAlpha <../types/0texture-01/gathercmpalpha-069>
GatherCmpBlue <../types/0texture-01/gathercmpblue-069>
GatherCmpGreen <../types/0texture-01/gathercmpgreen-069>
GatherCmpRed <../types/0texture-01/gathercmpred-069>
GatherGreen <../types/0texture-01/gathergreen-06>
GatherRed <../types/0texture-01/gatherred-06>
GetDimensions <../types/0texture-01/getdimensions-03>
GetSamplePosition <../types/0texture-01/getsampleposition-039>
Handle <../types/0texture-01/handle-0>
InterlockedAddF32 <../types/0texture-01/interlockedaddf32-0be>
Load <../types/0texture-01/load-0>
Sample <../types/0texture-01/sample-0>
SampleBias <../types/0texture-01/samplebias-06>
SampleCmp <../types/0texture-01/samplecmp-06>
SampleCmpLevel <../types/0texture-01/samplecmplevel-069>
SampleCmpLevelZero <../types/0texture-01/samplecmplevelzero-069e>
SampleGrad <../types/0texture-01/samplegrad-06>
SampleLevel <../types/0texture-01/samplelevel-06>
Store <../types/0texture-01/store-0>
TextureCoord <../types/0texture-01/texturecoord-07>
WriteSamplerFeedback <../types/0texture-01/writesamplerfeedback-05c>
WriteSamplerFeedbackBias <../types/0texture-01/writesamplerfeedbackbias-05ck>
WriteSamplerFeedbackGrad <../types/0texture-01/writesamplerfeedbackgrad-05ck>
WriteSamplerFeedbackLevel <../types/0texture-01/writesamplerfeedbacklevel-05ck>
init <../types/0texture-01/init>
kind <../types/0texture-01/kind>
queryFootprintCoarse <../types/0texture-01/queryfootprintcoarse-5e>
queryFootprintCoarseBias <../types/0texture-01/queryfootprintcoarsebias-5ek>
queryFootprintCoarseBiasClamp <../types/0texture-01/queryfootprintcoarsebiasclamp-5eko>
queryFootprintCoarseClamp <../types/0texture-01/queryfootprintcoarseclamp-5ek>
queryFootprintCoarseGrad <../types/0texture-01/queryfootprintcoarsegrad-5ek>
queryFootprintCoarseGradClamp <../types/0texture-01/queryfootprintcoarsegradclamp-5eko>
queryFootprintCoarseLevel <../types/0texture-01/queryfootprintcoarselevel-5ek>
queryFootprintFine <../types/0texture-01/queryfootprintfine-5e>
queryFootprintFineBias <../types/0texture-01/queryfootprintfinebias-5ei>
queryFootprintFineBiasClamp <../types/0texture-01/queryfootprintfinebiasclamp-5eim>
queryFootprintFineClamp <../types/0texture-01/queryfootprintfineclamp-5ei>
queryFootprintFineGrad <../types/0texture-01/queryfootprintfinegrad-5ei>
queryFootprintFineGradClamp <../types/0texture-01/queryfootprintfinegradclamp-5eim>
queryFootprintFineLevel <../types/0texture-01/queryfootprintfinelevel-5ei>
subscript <../types/0texture-01/subscript>
```

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
