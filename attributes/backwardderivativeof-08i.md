---
layout: stdlib-reference
---

# attribute [BackwardDerivativeOf]

## Description

<span class='code'>[<a href=".">BackwardDerivativeOf</a>(fn)]</span> is the back-reference version of <span class='code'>[<a href="../backwardderivative-08.md">BackwardDerivative</a>(derivFn)]</span>

When used to decorate a function, the decorated function is considered the backward-derivative
implementation of the referenced function <span class='code'>fn</span>.

Apart from this, the semantics of the custom derivative are the same as for
<span class='code'>[<a href="../backwardderivative-08.md">BackwardDerivative</a>(derivFn)]</span>


## Signature

<pre>
[<a href=".">BackwardDerivativeOf</a>(<a href=".#decl-function" class="code_param">function</a>)]
</pre>

## Parameters

####  <a id="decl-function"></a>function

