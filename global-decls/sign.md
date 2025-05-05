---
layout: stdlib-reference
---

# sign

## Description

Extract sign of value.



## Signature 

<pre>
<span class="code_keyword">int</span> <a href="/stdlib-reference/global-decls/sign">sign</a>&lt;<a href="/stdlib-reference/global-decls/sign#typeparam-T" class="code_type">T</a>&gt;(<a href="/stdlib-reference/global-decls/sign#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/sign#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/sign#typeparam-T" class="code_type">T</a> : __BuiltinSignedArithmeticType;

<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="/stdlib-reference/global-decls/sign#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/sign">sign</a>&lt;<a href="/stdlib-reference/global-decls/sign#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/sign#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/sign#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/sign#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/sign#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/sign#typeparam-T" class="code_type">T</a> : __BuiltinSignedArithmeticType;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<span class="code_keyword">int</span>, <a href="/stdlib-reference/global-decls/sign#decl-N" class="code_var">N</a>, <a href="/stdlib-reference/global-decls/sign#decl-M" class="code_var">M</a>&gt; <a href="/stdlib-reference/global-decls/sign">sign</a>&lt;<a href="/stdlib-reference/global-decls/sign#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/sign#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="/stdlib-reference/global-decls/sign#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/global-decls/sign#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/sign#decl-N" class="code_var">N</a>, <a href="/stdlib-reference/global-decls/sign#decl-M" class="code_var">M</a>&gt; <a href="/stdlib-reference/global-decls/sign#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/sign#typeparam-T" class="code_type">T</a> : __BuiltinSignedArithmeticType;

</pre>

## Generic Parameters

#### T: \_\_BuiltinSignedArithmeticType {#typeparam-T}
#### N  : int {#decl-N}
#### M  : int {#decl-M}

## Parameters

#### x  : [T](/stdlib-reference/global-decls/sign#typeparam-T) {#decl-x}
The value to extract the sign of.

#### x  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-x}
The value to extract the sign of.

#### x  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/t-0), [N](/stdlib-reference/types/matrix/index#decl-N), [M](/stdlib-reference/types/matrix/index#decl-M)\> {#decl-x}
The value to extract the sign of.


## Return value
-1 if <span class='code'><a href="/stdlib-reference/global-decls/sign#decl-x" class="code_param">x</a></span> is negative, 0 if <span class='code'><a href="/stdlib-reference/global-decls/sign#decl-x" class="code_param">x</a></span> is zero, and 1 if <span class='code'><a href="/stdlib-reference/global-decls/sign#decl-x" class="code_param">x</a></span> is positive.


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

#### wgsl
Available in all stages.

#### spirv
Available in all stages.



