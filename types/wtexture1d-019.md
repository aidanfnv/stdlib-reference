---
layout: stdlib-reference
---

# typealias WTexture1D\<T, int sampleCount, int format\>

## Description

Represents a handle to a write-only 1D texture.

## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="wtexture1d-019.html" class="code_type">WTexture1D</a>&lt;T, <span class="code_keyword">int</span> sampleCount, <span class="code_keyword">int</span> format&gt; = 
    <a href="0texture-01/index.html" class="code_type">_Texture</a>&lt;T, <a href="0_shape1d-028/index.html" class="code_type">__Shape1D</a>, 0, 0, sampleCount, 2, 0, 0, format&gt;;
</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [ITexelElement](../interfaces/itexelelement-016/index.html) = [vector](vector/index.html)\<float, 4\>
The texel type of the texture.

####  <a id="decl-sampleCount"></a>sampleCount  : int = 0
The number of samples in the texture, when the texture is multisampled.

####  <a id="decl-format"></a>format  : int = 0
The storage format of the texture.


## See also

Please refer to <span class='code'><a href="0texture-01/index.html" class="code_type">_Texture</a></span> for more information about texture types.


