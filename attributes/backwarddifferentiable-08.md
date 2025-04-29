---
layout: stdlib-reference
---

# attribute [BackwardDifferentiable]

## Description

Marks a function as being differentiable for backward-mode auto-diff.
Note that in the current implementation, this implies that the method
is also forward differentiable.

This attribute is equivalent to using <span class='code'>[<a href="">Differentiable</a>]</span>


## Signature

<pre>
[<a href="backwarddifferentiable-08">BackwardDifferentiable</a>(<a href="backwarddifferentiable-08#decl-order" class="code_param">order</a> : <span class="code_keyword">int</span>)]
</pre>

## Parameters

####  <a id="decl-order"></a>order  : int = 0

