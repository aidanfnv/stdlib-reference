---
layout: stdlib-reference
---

# min3

## Description

Minimum of 3 inputs.



## Signature 

<pre>
<a href="/stdlib-reference/global-decls/min3#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/min3">min3</a>&lt;<a href="/stdlib-reference/global-decls/min3#typeparam-T" class="code_type">T</a>&gt;(
    <a href="/stdlib-reference/global-decls/min3#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/min3#decl-x" class="code_param">x</a>,
    <a href="/stdlib-reference/global-decls/min3#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/min3#decl-y" class="code_param">y</a>,
    <a href="/stdlib-reference/global-decls/min3#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/min3#decl-z" class="code_param">z</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/min3#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/min3#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/min3#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/min3">min3</a>&lt;<a href="/stdlib-reference/global-decls/min3#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/min3#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/min3#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/min3#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/min3#decl-x" class="code_param">x</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/min3#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/min3#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/min3#decl-y" class="code_param">y</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/min3#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/min3#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/min3#decl-z" class="code_param">z</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/min3#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

#### T: [\_\_BuiltinFloatingPointType](/stdlib-reference/interfaces/0_builtinfloatingpointtype-029hm/index) {#typeparam-T}
#### N  : int {#decl-N}

## Parameters

#### x  : [T](/stdlib-reference/global-decls/min3#typeparam-T) {#decl-x}
The first value to compare.

#### y  : [T](/stdlib-reference/global-decls/min3#typeparam-T) {#decl-y}
The second value to compare.

#### z  : [T](/stdlib-reference/global-decls/min3#typeparam-T) {#decl-z}
The third value to compare.

#### x  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-x}
The first value to compare.

#### y  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-y}
The second value to compare.

#### z  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-z}
The third value to compare.


## Return value
The smallest of the three values, element-wise if vector typed.


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



