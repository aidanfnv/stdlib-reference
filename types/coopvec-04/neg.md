---
layout: stdlib-reference
---

# CoopVec\<T, int N\>\.neg

## Description

Returns a new cooperative vector where each component has its sign negated.



## Signature 

<pre>
<a href="index.html" class="code_type">CoopVec</a>&lt;<a href="index.html#typeparam-T" class="code_type">T</a>, <a href="index.html#decl-N" class="code_var">N</a>&gt; <a href="index.html" class="code_type">CoopVec</a>&lt;<a href="index.html#typeparam-T" class="code_type">T</a>, <span class="code_keyword">int</span> <a href="index.html#decl-N" class="code_var">N</a>&gt;.<a href="neg.html">neg</a>()
    <span class='code_keyword'>where</span> <a href="index.html#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Return value
A new cooperative vector containing the negated values.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

Requires capability: `hlsl_coopvec_poc`.
#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvCooperativeVectorNV`.


