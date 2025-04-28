---
layout: stdlib-reference
---

# attribute [PreferRecompute]

## Description

Mark a differentiable function to prefer recomputation over checkpointing when a value computed in the primal pass is needed
during backward derivative propagation.


## Signature

<pre>
[<a href=".html">PreferRecompute</a>(<a href=".html#decl-behavior" class="code_param">behavior</a> : <a href="../../types/sideeffectbehavior-04a/index.html" class="code_type">SideEffectBehavior</a>)]
</pre>

## Parameters

####  <a id="decl-behavior"></a>behavior  : [SideEffectBehavior](../../types/sideeffectbehavior-04a/index.html) = [SideEffectBehavior](../../types/sideeffectbehavior-04a/index.html)\.[Warn](../../types/sideeffectbehavior-04a/index.html#decl-Warn)

