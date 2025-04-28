---
layout: stdlib-reference
---

# RayQuery\<rayFlagsGeneric:uint\>\.CandidateRayInstanceId

## Description

Gets the instance ID of the candidate hit.



## Signature 

<pre>
<span class="code_keyword">int</span> <a href="../index.html" class="code_type">RayQuery</a>&lt;<a href="../index.html#decl-rayFlagsGeneric" class="code_var">rayFlagsGeneric</a>:<span class="code_keyword">uint</span>&gt;.<a href=".html">CandidateRayInstanceId</a>();

</pre>

## Return value
System-assigned instance identifier

## Remarks
GLSL/SPIRV only


## Availability and Requirements

Defined for the following targets:

#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvRayQueryKHR`.


