---
layout: stdlib-reference
---

# ReorderThread

## Description

Reorders threads based on a coherence hint value. NumCoherenceHintBits indicates how many of
the least significant bits of CoherenceHint should be considered during reordering (max: 16).
Applications should set this to the lowest value required to represent all possible values in
CoherenceHint. For best performance, all threads should provide the same value for
NumCoherenceHintBits.
Where possible, reordering will also attempt to retain locality in the thread429496726642949671684294967193s launch indices
(DispatchRaysIndex in DXR).




## Signature 

<pre>
<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/reorderthread-07">ReorderThread</a>(
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/global-decls/reorderthread-07#decl-CoherenceHint" class="code_param">CoherenceHint</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/global-decls/reorderthread-07#decl-NumCoherenceHintBitsFromLSB" class="code_param">NumCoherenceHintBitsFromLSB</a>);

<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/reorderthread-07">ReorderThread</a>(
    <a href="/stdlib-reference/types/hitobject-03/index" class="code_type">HitObject</a> <a href="/stdlib-reference/global-decls/reorderthread-07#decl-HitOrMiss" class="code_param">HitOrMiss</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/global-decls/reorderthread-07#decl-CoherenceHint" class="code_param">CoherenceHint</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/global-decls/reorderthread-07#decl-NumCoherenceHintBitsFromLSB" class="code_param">NumCoherenceHintBitsFromLSB</a>);

<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/reorderthread-07">ReorderThread</a>(<a href="/stdlib-reference/types/hitobject-03/index" class="code_type">HitObject</a> <a href="/stdlib-reference/global-decls/reorderthread-07#decl-HitOrMiss" class="code_param">HitOrMiss</a>);

</pre>

## Parameters

#### CoherenceHint  : uint {#decl-CoherenceHint}
#### NumCoherenceHintBitsFromLSB  : uint {#decl-NumCoherenceHintBitsFromLSB}
#### HitOrMiss  : [HitObject](/stdlib-reference/types/hitobject-03/index) {#decl-HitOrMiss}

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in `raygen` stage only.

Requires capability: `hlsl_nvapi`.
#### glsl
Available in `raygen` stage only.

#### spirv
Available in `raygen` stage only.

Requires capabilities: `spvRayTracingKHR`, `spvShaderInvocationReorderNV`.


