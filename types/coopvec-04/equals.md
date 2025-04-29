---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.equals

## Description

Checks if this cooperative vector is equal to another cooperative vector by comparing all elements.



## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="equals">equals</a>(<a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>&gt; <a href="equals#decl-other" class="code_param">other</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Parameters

####  <a id="decl-other"></a>other  : [CoopVec](../types/coopvec-04/index)\<[T](../types/coopvec-04/index#typeparam-T), [N](../types/coopvec-04/index#decl-N)\>
The cooperative vector to compare against.


## Return value
True if all corresponding elements are equal, false otherwise.


