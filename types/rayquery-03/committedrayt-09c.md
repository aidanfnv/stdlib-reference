---
layout: stdlib-reference
---

# RayQuery\<uint rayFlagsGeneric\>\.CommittedRayT

## Description

Gets the distance to the committed (closest) hit.



## Signature 

<pre>
<span class="code_keyword">float</span> <a href="index.html" class="code_type">RayQuery</a>&lt;<span class="code_keyword">uint</span> <a href="index.html#decl-rayFlagsGeneric" class="code_var">rayFlagsGeneric</a>&gt;.<a href="committedrayt-09c.html">CommittedRayT</a>();

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


