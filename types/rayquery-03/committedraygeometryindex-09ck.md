---
layout: stdlib-reference
---

# RayQuery\<uint rayFlagsGeneric\>\.CommittedRayGeometryIndex

## Description

Gets the geometry index for the committed hit.



## Signature 

<pre>
<span class="code_keyword">int</span> <a href="index.html" class="code_type">RayQuery</a>&lt;<span class="code_keyword">uint</span> <a href="index.html#decl-rayFlagsGeneric" class="code_var">rayFlagsGeneric</a>&gt;.<a href="committedraygeometryindex-09ck.html">CommittedRayGeometryIndex</a>();

</pre>

## Return value
Zero-based index of the geometry in the instance

## Remarks
GLSL/SPIRV only


## Availability and Requirements

Defined for the following targets:

#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvRayQueryKHR`.


