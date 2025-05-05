---
layout: stdlib-reference
---

# RayQuery\<rayFlagsGeneric:uint\>\.CommittedRayT

## Description

Gets the distance to the committed (closest) hit.



## Signature 

<pre>
<span class="code_keyword">float</span> <a href="/stdlib-reference/types/rayquery-03/index" class="code_type">RayQuery</a>&lt;<a href="/stdlib-reference/types/rayquery-03/index#decl-rayFlagsGeneric" class="code_var">rayFlagsGeneric</a>:<span class="code_keyword">uint</span>&gt;.<a href="/stdlib-reference/types/rayquery-03/committedrayt-09c">CommittedRayT</a>();

</pre>

## Return value
t-value along the ray where the closest hit occurred


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvRayQueryKHR`.


