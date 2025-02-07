---
layout: stdlib-reference
---

# WaveMultiPrefixBitOr

## Description





## Signature 

<pre>
/// Requires Capability Set 1:
<a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi">WaveMultiPrefixBitOr</a>&lt;<a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#typeparam-T" class="code_type">T</a>&gt;(
    <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-expr" class="code_param">expr</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-mask" class="code_param">mask</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 1:
<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi">WaveMultiPrefixBitOr</a>&lt;<a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-expr" class="code_param">expr</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-mask" class="code_param">mask</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

/// Requires Capability Set 2:
<a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-N" class="code_var">N</a>, <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-M" class="code_var">M</a>&gt; <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi">WaveMultiPrefixBitOr</a>&lt;<a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="/stdlib-reference/types/matrix/index" class="code_type">matrix</a>&lt;<a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-N" class="code_var">N</a>, <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-M" class="code_var">M</a>&gt; <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-expr" class="code_param">expr</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#decl-mask" class="code_param">mask</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/0_builtinarithmetictype-029j/index" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

#### T: [\_\_BuiltinArithmeticType](/stdlib-reference/interfaces/0_builtinarithmetictype-029j/index) {#typeparam-T}
#### N  : int {#decl-N}
#### M  : int {#decl-M}

## Parameters

#### expr  : [T](/stdlib-reference/global-decls/wavemultiprefixbitor-049fi#typeparam-T) {#decl-expr}
#### mask  : [vector](/stdlib-reference/types/vector/index)\<uint, 4\> {#decl-mask}
#### expr  : [vector](/stdlib-reference/types/vector/index)\<[T](/stdlib-reference/types/vector/index#typeparam-T), [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-expr}
#### expr  : [matrix](/stdlib-reference/types/matrix/index)\<[T](/stdlib-reference/types/matrix/t-0), [N](/stdlib-reference/types/matrix/index#decl-N), [M](/stdlib-reference/types/matrix/index#decl-M)\> {#decl-expr}

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cuda
Available in all stages.


### Capability Set 2

Defined for the following targets:

#### hlsl
Available in all stages.

#### cuda
Available in all stages.



