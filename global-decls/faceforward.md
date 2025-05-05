---
layout: stdlib-reference
---

# faceforward

## Description

Flip vector to face forward, if needed.



## Signature 

<pre>
<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/faceforward#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/faceforward#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/faceforward">faceforward</a>&lt;<a href="/stdlib-reference/global-decls/faceforward#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/faceforward#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/faceforward#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/faceforward#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/faceforward#decl-n" class="code_param">n</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/faceforward#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/faceforward#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/faceforward#decl-i" class="code_param">i</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/faceforward#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/faceforward#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/faceforward#decl-ng" class="code_param">ng</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/faceforward#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

#### T: [\_\_BuiltinFloatingPointType](/stdlib-reference/interfaces/0_builtinfloatingpointtype-029hm/index) {#typeparam-T}
#### N  : int {#decl-N}

## Parameters

#### n  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-n}
The vector to orient.

#### i  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-i}
The incident vector.

#### ng  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-ng}
The geometric normal vector.


## Return value
<span class='code'><a href="/stdlib-reference/global-decls/faceforward#decl-n" class="code_param">n</a></span> if the dot product of <span class='code'><a href="/stdlib-reference/global-decls/faceforward#decl-ng" class="code_param">ng</a></span> and <span class='code'><a href="/stdlib-reference/global-decls/faceforward#decl-i" class="code_param">i</a></span> is less than 0, otherwise <span class='code'>-<a href="/stdlib-reference/global-decls/faceforward#decl-n" class="code_param">n</a></span>.


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

#### wgsl
Available in all stages.

#### spirv
Available in all stages.



