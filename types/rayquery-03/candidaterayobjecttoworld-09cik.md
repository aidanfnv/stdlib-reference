---
layout: stdlib-reference
---

# RayQuery\<rayFlagsGeneric:uint\>\.CandidateRayObjectToWorld

## Description

Gets the object-to-world transform matrix for the candidate hit instance.



## Signature 

<pre>
<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<span class="code_keyword">float</span>, 4, 3&gt; <a href="/stdlib-reference/types/rayquery-03/index" class="code_type">RayQuery</a>&lt;<a href="/stdlib-reference/types/rayquery-03/index#decl-rayFlagsGeneric" class="code_var">rayFlagsGeneric</a>:<span class="code_keyword">uint</span>&gt;.<a href="/stdlib-reference/types/rayquery-03/candidaterayobjecttoworld-09cik">CandidateRayObjectToWorld</a>();

</pre>

## Return value
4x3 matrix transforming from object to world space

## Remarks
GLSL/SPIRV only


## Availability and Requirements

Defined for the following targets:

#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvRayQueryKHR`.


