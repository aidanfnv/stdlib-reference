---
layout: stdlib-reference
---

# RayQuery\<uint rayFlagsGeneric\>\.CommittedObjectToWorld3x4

## Description

Gets the object-to-world transform as a 3x4 matrix.



## Signature 

<pre>
<a href="../matrix/index.html" class="code_type">matrix</a>&lt;<span class="code_keyword">float</span>, 3, 4&gt; <a href="index.html" class="code_type">RayQuery</a>&lt;<span class="code_keyword">uint</span> <a href="index.html#decl-rayFlagsGeneric" class="code_var">rayFlagsGeneric</a>&gt;.<a href="committedobjecttoworld3x4-09fh.html">CommittedObjectToWorld3x4</a>();

</pre>

## Return value
3x4 matrix transforming from object to world space

## Remarks
Available for both candidate and committed hits


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvRayQueryKHR`.


