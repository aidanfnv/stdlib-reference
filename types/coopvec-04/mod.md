---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.mod

## Description

Performs component-wise remainder operation between two cooperative vectors.



## Signature 

<pre>
<a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>&gt; <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="mod">mod</a>(<a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>&gt; <a href="mod#decl-other" class="code_param">other</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Parameters

####  <a id="decl-other"></a>other  : [CoopVec](../types/coopvec-04/index)\<[T](../types/coopvec-04/index#typeparam-T), [N](../types/coopvec-04/index#decl-N)\>
The cooperative vector to compute the remainder with.


## Return value
A new cooperative vector containing the remainder of the division between corresponding components.


