---
layout: stdlib-reference
---

# QuadReadAcrossX

## Description





## Signature 

<pre>
<a href="quadreadacrossx-048e.md#typeparam-T" class="code_type">T</a> <a href="quadreadacrossx-048e.md">QuadReadAcrossX</a>&lt;<a href="quadreadacrossx-048e.md#typeparam-T" class="code_type">T</a>&gt;(<a href="quadreadacrossx-048e.md#typeparam-T" class="code_type">T</a> <a href="quadreadacrossx-048e.md#decl-localValue" class="code_param">localValue</a>)
    <span class='code_keyword'>where</span> <a href="quadreadacrossx-048e.md#typeparam-T" class="code_type">T</a> : __BuiltinType;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="quadreadacrossx-048e.md#typeparam-T" class="code_type">T</a>, <a href="quadreadacrossx-048e.md#decl-N" class="code_var">N</a>&gt; <a href="quadreadacrossx-048e.md">QuadReadAcrossX</a>&lt;<a href="quadreadacrossx-048e.md#typeparam-T" class="code_type">T</a>, <a href="quadreadacrossx-048e.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="quadreadacrossx-048e.md#typeparam-T" class="code_type">T</a>, <a href="quadreadacrossx-048e.md#decl-N" class="code_var">N</a>&gt; <a href="quadreadacrossx-048e.md#decl-localValue" class="code_param">localValue</a>)
    <span class='code_keyword'>where</span> <a href="quadreadacrossx-048e.md#typeparam-T" class="code_type">T</a> : __BuiltinType;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="quadreadacrossx-048e.md#typeparam-T" class="code_type">T</a>, <a href="quadreadacrossx-048e.md#decl-N" class="code_var">N</a>, <a href="quadreadacrossx-048e.md#decl-M" class="code_var">M</a>&gt; <a href="quadreadacrossx-048e.md">QuadReadAcrossX</a>&lt;<a href="quadreadacrossx-048e.md#typeparam-T" class="code_type">T</a>, <a href="quadreadacrossx-048e.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="quadreadacrossx-048e.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="quadreadacrossx-048e.md#typeparam-T" class="code_type">T</a>, <a href="quadreadacrossx-048e.md#decl-N" class="code_var">N</a>, <a href="quadreadacrossx-048e.md#decl-M" class="code_var">M</a>&gt; <a href="quadreadacrossx-048e.md#decl-localValue" class="code_param">localValue</a>)
    <span class='code_keyword'>where</span> <a href="quadreadacrossx-048e.md#typeparam-T" class="code_type">T</a> : __BuiltinType;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: \_\_BuiltinType
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-localValue"></a>localValue  : [T](quadreadacrossx-048e.md#typeparam-T)
####  <a id="decl-localValue"></a>localValue  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-localValue"></a>localValue  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>

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

Requires capability: `spvGroupNonUniformQuad`.



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
