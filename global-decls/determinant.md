---
layout: stdlib-reference
---

# determinant

## Description

Compute matrix determinant.



## Signature 

<pre>
<a href="determinant#typeparam-T" class="code_type">T</a> <a href="determinant">determinant</a>&lt;<a href="determinant#typeparam-T" class="code_type">T</a>, <a href="determinant#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="determinant#typeparam-T" class="code_type">T</a>, <a href="determinant#decl-N" class="code_var">N</a>, <a href="determinant#decl-N" class="code_var">N</a>&gt; <a href="determinant#decl-m" class="code_param">m</a>)
    <span class='code_keyword'>where</span> <a href="determinant#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-m"></a>m  : [matrix](../types/matrix/index)\<[T](), [N](../types/matrix/index#decl-N), [N](../types/matrix/index#decl-N)\>
The matrix.


## Return value
The determinant of the matrix.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### metal
Available in all stages.

#### wgsl
Available in all stages.

#### spirv
Available in all stages.



