---
layout: stdlib-reference
---

# typealias RasterizerOrderedTexture3D\<T, sampleCount:int, format:int\>

## Description

Represents a handle to a rasterizer-ordered 3D texture.

## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="rasterizerorderedtexture3d-0ahp" class="code_type">RasterizerOrderedTexture3D</a>&lt;T, sampleCount:<span class="code_keyword">int</span>, format:<span class="code_keyword">int</span>&gt; = 
    <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;T, <a href="../types/0_shape3d-028/index" class="code_type">__Shape3D</a>, 0, 0, sampleCount, 3, 0, 0, format&gt;;
</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [ITexelElement](../interfaces/itexelelement-016/index) = [vector](../types/vector/index)\<float, 4\>
The texel type of the texture.

####  <a id="decl-sampleCount"></a>sampleCount  : int = 0
The number of samples in the texture, when the texture is multisampled.

####  <a id="decl-format"></a>format  : int = 0
The storage format of the texture.


## See also

Please refer to <span class='code'><a href="../types/0texture-01/index" class="code_type">_Texture</a></span> for more information about texture types.


