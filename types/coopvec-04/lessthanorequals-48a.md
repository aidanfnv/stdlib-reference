---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.lessThanOrEquals

## Description

Compares two cooperative vectors lexicographically.



## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="lessthanorequals-48a">lessThanOrEquals</a>(<a href="../types/coopvec-04/index" class="code_type">CoopVec</a>&lt;<a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a>, <a href="../types/coopvec-04/index#decl-N" class="code_var">N</a>&gt; <a href="lessthanorequals-48a#decl-other" class="code_param">other</a>)
    <span class='code_keyword'>where</span> <a href="../types/coopvec-04/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Parameters

####  <a id="decl-other"></a>other  : [CoopVec](../types/coopvec-04/index)\<[T](../types/coopvec-04/index#typeparam-T), [N](../types/coopvec-04/index#decl-N)\>
The cooperative vector to compare against.


## Return value
True if this vector is lexicographically less than or equal to the other vector.

## Remarks
This function exists only to conform to IComparable. For cooperative vectors,
lexicographical comparison has limited practical use since the vectors are meant for
parallel computation rather than ordering.


