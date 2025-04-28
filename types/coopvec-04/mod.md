---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.mod

## Description

Performs component-wise remainder operation between two cooperative vectors.



## Signature 

<pre>
<a href="../types/coopvec-04/index.html" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index.html#decl-N" class="code_var">N</a>&gt; <a href="../types/coopvec-04/index.html" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="mod.html">mod</a>(<a href="../types/coopvec-04/index.html" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index.html#decl-N" class="code_var">N</a>&gt; <a href="mod.html#decl-other" class="code_param">other</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Parameters

####  <a id="decl-other"></a>other  : [CoopVec](../types/coopvec-04/index.html)\<[T](../types/coopvec-04/index.html#typeparam-T), [N](../types/coopvec-04/index.html#decl-N)\>
The cooperative vector to compute the remainder with.


## Return value
A new cooperative vector containing the remainder of the division between corresponding components.


