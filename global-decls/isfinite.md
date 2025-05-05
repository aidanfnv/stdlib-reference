---
layout: stdlib-reference
---

# isfinite

## Description

Test if a floating-point value is finite.



## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="/stdlib-reference/global-decls/isfinite">isfinite</a>&lt;<a href="/stdlib-reference/global-decls/isfinite#typeparam-T" class="code_type">T</a>&gt;(<a href="/stdlib-reference/global-decls/isfinite#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/isfinite#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/isfinite#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">bool</span>, <a href="/stdlib-reference/global-decls/isfinite#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/isfinite">isfinite</a>&lt;<a href="/stdlib-reference/global-decls/isfinite#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/isfinite#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/isfinite#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/isfinite#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/isfinite#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/isfinite#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<span class="code_keyword">bool</span>, <a href="/stdlib-reference/global-decls/isfinite#decl-N" class="code_var">N</a>, <a href="/stdlib-reference/global-decls/isfinite#decl-M" class="code_var">M</a>&gt; <a href="/stdlib-reference/global-decls/isfinite">isfinite</a>&lt;<a href="/stdlib-reference/global-decls/isfinite#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/isfinite#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="/stdlib-reference/global-decls/isfinite#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/global-decls/isfinite#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/isfinite#decl-N" class="code_var">N</a>, <a href="/stdlib-reference/global-decls/isfinite#decl-M" class="code_var">M</a>&gt; <a href="/stdlib-reference/global-decls/isfinite#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/isfinite#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

#### T: [\_\_BuiltinFloatingPointType](/stdlib-reference/interfaces/0_builtinfloatingpointtype-029hm/index) {#typeparam-T}
#### N  : int {#decl-N}
#### M  : int {#decl-M}

## Parameters

#### x  : [T](/stdlib-reference/global-decls/isfinite#typeparam-T) {#decl-x}
The input value.

#### x  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-x}
The input value.

#### x  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/t-0), [N](/stdlib-reference/types/matrix/index#decl-N), [M](/stdlib-reference/types/matrix/index#decl-M)\> {#decl-x}
The input value.


## Return value
<span class='code'>true</span> if <span class='code'><a href="/stdlib-reference/global-decls/isfinite#decl-x" class="code_param">x</a></span> is finite, <span class='code'>false</span> otherwise.


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



