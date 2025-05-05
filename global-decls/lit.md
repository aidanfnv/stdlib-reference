---
layout: stdlib-reference
---

# lit

## Description

Legacy lighting function (obsolete).




## Signature 

<pre>
<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, 4&gt; <a href="/stdlib-reference/global-decls/lit">lit</a>(
    <span class="code_keyword">float</span> <a href="/stdlib-reference/global-decls/lit#decl-n_dot_l" class="code_param">n_dot_l</a>,
    <span class="code_keyword">float</span> <a href="/stdlib-reference/global-decls/lit#decl-n_dot_h" class="code_param">n_dot_h</a>,
    <span class="code_keyword">float</span> <a href="/stdlib-reference/global-decls/lit#decl-m" class="code_param">m</a>);

</pre>

## Parameters

#### n\_dot\_l  : float {#decl-n_dot_l}
The dot product of the normal and light vectors.

#### n\_dot\_h  : float {#decl-n_dot_h}
The dot product of the normal and half-angle vectors.

#### m  : float {#decl-m}
The material shininess factor.


## Return value
The lighting coefficients, (ambient, diffuse, specular, 1.0).

## Remarks
In HLSL, this function is implemented as an intrinsic. It is emulated for other targets.

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### spirv
Available in all stages.



