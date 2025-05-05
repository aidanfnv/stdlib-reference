---
layout: stdlib-reference
---

# pack\_clamp\_s8

## Description

Pack a vector of 4 signed 32/16 bit integers into a packed value of 4 8-bit integers,
clamping each value to the range [-128, 127] to ensure it fits within 8 bits.




## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="/stdlib-reference/global-decls/pack_clamp_s8">pack_clamp_s8</a>(<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, 4&gt; <a href="/stdlib-reference/global-decls/pack_clamp_s8#decl-unpackedValue" class="code_param">unpackedValue</a>);

<span class="code_keyword">uint</span> <a href="/stdlib-reference/global-decls/pack_clamp_s8">pack_clamp_s8</a>(<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;int16_t, 4&gt; <a href="/stdlib-reference/global-decls/pack_clamp_s8#decl-unpackedValue" class="code_param">unpackedValue</a>);

</pre>

## Parameters

#### unpackedValue  : [vector](/stdlib-reference/types/vector/index)\<int, 4\> {#decl-unpackedValue}
#### unpackedValue  : [vector](/stdlib-reference/types/vector/index)\<int16\_t, 4\> {#decl-unpackedValue}

## Availability and Requirements

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



