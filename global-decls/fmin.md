---
layout: stdlib-reference
---

# fmin

## Description

Floating-point minimum.



## Signature 

<pre>
<a href="fmin.md#typeparam-T" class="code_type">T</a> <a href="fmin.md">fmin</a>&lt;<a href="fmin.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="fmin.md#typeparam-T" class="code_type">T</a> <a href="fmin.md#decl-x" class="code_param">x</a>,
    <a href="fmin.md#typeparam-T" class="code_type">T</a> <a href="fmin.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="fmin.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="fmin.md#typeparam-T" class="code_type">T</a>, <a href="fmin.md#decl-N" class="code_var">N</a>&gt; <a href="fmin.md">fmin</a>&lt;<a href="fmin.md#typeparam-T" class="code_type">T</a>, <a href="fmin.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="fmin.md#typeparam-T" class="code_type">T</a>, <a href="fmin.md#decl-N" class="code_var">N</a>&gt; <a href="fmin.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="fmin.md#typeparam-T" class="code_type">T</a>, <a href="fmin.md#decl-N" class="code_var">N</a>&gt; <a href="fmin.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="fmin.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](fmin.md#typeparam-T)
The first value to compare.

####  <a id="decl-y"></a>y  : [T](fmin.md#typeparam-T)
The second value to compare.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The first value to compare.

####  <a id="decl-y"></a>y  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The second value to compare.


## Return value
The smaller of the two values, element-wise if vector typed.

## Remarks
Result is <span class='code'><a href="fmin.md#decl-x" class="code_param">x</a></span> if <span class='code'><a href="fmin.md#decl-x" class="code_param">x</a></span> < <span class='code'><a href="fmin.md#decl-y" class="code_param">y</a></span>, either <span class='code'><a href="fmin.md#decl-x" class="code_param">x</a></span> or <span class='code'><a href="fmin.md#decl-y" class="code_param">y</a></span> if both <span class='code'><a href="fmin.md#decl-x" class="code_param">x</a></span> and <span class='code'><a href="fmin.md#decl-y" class="code_param">y</a></span> are zeros, otherwise <span class='code'><a href="fmin.md#decl-y" class="code_param">y</a></span>. Which operand is the result is undefined if one of the operands is a NaN.


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
