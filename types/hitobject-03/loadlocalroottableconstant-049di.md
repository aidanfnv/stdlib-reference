---
layout: stdlib-reference
---

# HitObject\.LoadLocalRootTableConstant

## Description

Loads a root constant from the local root table referenced by the hit object. Valid if the hit object
represents a hit or a miss. RootConstantOffsetInBytes must be a multiple of 4.




## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/index" class="code_type">HitObject</a>.<a href="/stdlib-reference/types/hitobject-03/loadlocalroottableconstant-049di">LoadLocalRootTableConstant</a>(<span class="code_keyword">uint</span> <a href="/stdlib-reference/types/hitobject-03/loadlocalroottableconstant-049di#decl-RootConstantOffsetInBytes" class="code_param">RootConstantOffsetInBytes</a>);

</pre>

## Parameters

#### RootConstantOffsetInBytes  : uint {#decl-RootConstantOffsetInBytes}

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

Requires capability: `hlsl_nvapi`.


