---
layout: stdlib-reference
---

# WaveReadLaneFirst

## Description





## Signature 

<pre>
<a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c">WaveReadLaneFirst</a>&lt;<a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#typeparam-T" class="code_type">T</a>&gt;(<a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#decl-expr" class="code_param">expr</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#typeparam-T" class="code_type">T</a> : __BuiltinType;

<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c">WaveReadLaneFirst</a>&lt;<a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#decl-expr" class="code_param">expr</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#typeparam-T" class="code_type">T</a> : __BuiltinType;

<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#decl-N" class="code_var">N</a>, <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#decl-M" class="code_var">M</a>&gt; <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c">WaveReadLaneFirst</a>&lt;<a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#decl-N" class="code_var">N</a>, <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#decl-M" class="code_var">M</a>&gt; <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#decl-expr" class="code_param">expr</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/wavereadlanefirst-048c#typeparam-T" class="code_type">T</a> : __BuiltinType;

</pre>

## Generic Parameters

#### T: \_\_BuiltinType {#typeparam-T}
#### N  : int {#decl-N}
#### M  : int {#decl-M}

## Parameters

#### expr  : [T](/stdlib-reference/global-decls/wavereadlanefirst-048c#typeparam-T) {#decl-expr}
#### expr  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-expr}
#### expr  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/t-0), [N](/stdlib-reference/types/matrix/index#decl-N), [M](/stdlib-reference/types/matrix/index#decl-M)\> {#decl-expr}

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvGroupNonUniformBallot`.


