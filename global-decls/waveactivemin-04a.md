---
layout: stdlib-reference
---

# WaveActiveMin

## Description





## Signature 

<pre>
<a href="waveactivemin-04a.md#typeparam-T" class="code_type">T</a> <a href="waveactivemin-04a.md">WaveActiveMin</a>&lt;<a href="waveactivemin-04a.md#typeparam-T" class="code_type">T</a>&gt;(<a href="waveactivemin-04a.md#typeparam-T" class="code_type">T</a> <a href="waveactivemin-04a.md#decl-expr" class="code_param">expr</a>)
    <span class='code_keyword'>where</span> <a href="waveactivemin-04a.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="waveactivemin-04a.md#typeparam-T" class="code_type">T</a>, <a href="waveactivemin-04a.md#decl-N" class="code_var">N</a>&gt; <a href="waveactivemin-04a.md">WaveActiveMin</a>&lt;<a href="waveactivemin-04a.md#typeparam-T" class="code_type">T</a>, <a href="waveactivemin-04a.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="waveactivemin-04a.md#typeparam-T" class="code_type">T</a>, <a href="waveactivemin-04a.md#decl-N" class="code_var">N</a>&gt; <a href="waveactivemin-04a.md#decl-expr" class="code_param">expr</a>)
    <span class='code_keyword'>where</span> <a href="waveactivemin-04a.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="waveactivemin-04a.md#typeparam-T" class="code_type">T</a>, <a href="waveactivemin-04a.md#decl-N" class="code_var">N</a>, <a href="waveactivemin-04a.md#decl-M" class="code_var">M</a>&gt; <a href="waveactivemin-04a.md">WaveActiveMin</a>&lt;<a href="waveactivemin-04a.md#typeparam-T" class="code_type">T</a>, <a href="waveactivemin-04a.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="waveactivemin-04a.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="waveactivemin-04a.md#typeparam-T" class="code_type">T</a>, <a href="waveactivemin-04a.md#decl-N" class="code_var">N</a>, <a href="waveactivemin-04a.md#decl-M" class="code_var">M</a>&gt; <a href="waveactivemin-04a.md#decl-expr" class="code_param">expr</a>)
    <span class='code_keyword'>where</span> <a href="waveactivemin-04a.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-expr"></a>expr  : [T](waveactivemin-04a.md#typeparam-T)
####  <a id="decl-expr"></a>expr  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-expr"></a>expr  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### wgsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvGroupNonUniformArithmetic`.



<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
