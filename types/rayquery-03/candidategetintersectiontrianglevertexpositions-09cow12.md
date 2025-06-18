---
layout: stdlib-reference
---

# RayQuery\<uint rayFlagsGeneric\>\.CandidateGetIntersectionTriangleVertexPositions

## Description

Gets the triangle vertex positions for an intersection.



## Signature 

<pre>
<a href="../vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 3&gt;[3] <a href="index.html" class="code_type">RayQuery</a>&lt;<span class="code_keyword">uint</span> <a href="index.html#decl-rayFlagsGeneric" class="code_var">rayFlagsGeneric</a>&gt;.<a href="candidategetintersectiontrianglevertexpositions-09cow12.html">CandidateGetIntersectionTriangleVertexPositions</a>();

</pre>

## Return value
Array of three vertex positions in world space

## Remarks
Requires ray query position fetch extension


## Availability and Requirements

Defined for the following targets:

#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvRayQueryPositionFetchKHR`.


