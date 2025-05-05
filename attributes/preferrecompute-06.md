---
layout: stdlib-reference
---

# attribute [PreferRecompute]

## Description

Mark a differentiable function to prefer recomputation over checkpointing when a value computed in the primal pass is needed
during backward derivative propagation.


## Signature

<pre>
[<a href="/stdlib-reference/attributes/preferrecompute-06">PreferRecompute</a>(<a href="/stdlib-reference/attributes/preferrecompute-06#decl-behavior" class="code_param">behavior</a> : <a href="/stdlib-reference/types/sideeffectbehavior-04a/index" class="code_type">SideEffectBehavior</a>)]
</pre>

## Parameters

#### behavior  : [SideEffectBehavior](/stdlib-reference/types/sideeffectbehavior-04a/index) = [SideEffectBehavior](/stdlib-reference/types/sideeffectbehavior-04a/index)\.[Warn](/stdlib-reference/types/sideeffectbehavior-04a/index#decl-Warn) {#decl-behavior}

