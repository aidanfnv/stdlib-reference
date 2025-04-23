---
layout: stdlib-reference
---

# ldexp

## Description

Construct float from mantissa and exponent.



## Signature 

<pre>
<a href="ldexp.md#typeparam-T" class="code_type">T</a> <a href="ldexp.md">ldexp</a>&lt;<a href="ldexp.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="ldexp.md#typeparam-T" class="code_type">T</a> <a href="ldexp.md#decl-x" class="code_param">x</a>,
    <a href="ldexp.md#typeparam-T" class="code_type">T</a> <a href="ldexp.md#decl-exp" class="code_param">exp</a>)
    <span class='code_keyword'>where</span> <a href="ldexp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="ldexp.md#typeparam-T" class="code_type">T</a>, <a href="ldexp.md#decl-N" class="code_var">N</a>&gt; <a href="ldexp.md">ldexp</a>&lt;<a href="ldexp.md#typeparam-T" class="code_type">T</a>, <a href="ldexp.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="ldexp.md#typeparam-T" class="code_type">T</a>, <a href="ldexp.md#decl-N" class="code_var">N</a>&gt; <a href="ldexp.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="ldexp.md#typeparam-T" class="code_type">T</a>, <a href="ldexp.md#decl-N" class="code_var">N</a>&gt; <a href="ldexp.md#decl-exp" class="code_param">exp</a>)
    <span class='code_keyword'>where</span> <a href="ldexp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="ldexp.md#typeparam-T" class="code_type">T</a>, <a href="ldexp.md#decl-N" class="code_var">N</a>, <a href="ldexp.md#decl-M" class="code_var">M</a>&gt; <a href="ldexp.md">ldexp</a>&lt;<a href="ldexp.md#typeparam-T" class="code_type">T</a>, <a href="ldexp.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="ldexp.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="ldexp.md#typeparam-T" class="code_type">T</a>, <a href="ldexp.md#decl-N" class="code_var">N</a>, <a href="ldexp.md#decl-M" class="code_var">M</a>&gt; <a href="ldexp.md#decl-x" class="code_param">x</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="ldexp.md#typeparam-T" class="code_type">T</a>, <a href="ldexp.md#decl-N" class="code_var">N</a>, <a href="ldexp.md#decl-M" class="code_var">M</a>&gt; <a href="ldexp.md#decl-exp" class="code_param">exp</a>)
    <span class='code_keyword'>where</span> <a href="ldexp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="ldexp.md#typeparam-T" class="code_type">T</a> <a href="ldexp.md">ldexp</a>&lt;<a href="ldexp.md#typeparam-T" class="code_type">T</a>, <a href="ldexp.md#typeparam-E" class="code_type">E</a>&gt;(
    <a href="ldexp.md#typeparam-T" class="code_type">T</a> <a href="ldexp.md#decl-x" class="code_param">x</a>,
    <a href="ldexp.md#typeparam-E" class="code_type">E</a> <a href="ldexp.md#decl-exp" class="code_param">exp</a>)
    <span class='code_keyword'>where</span> <a href="ldexp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="ldexp.md#typeparam-E" class="code_type">E</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="ldexp.md#typeparam-T" class="code_type">T</a>, <a href="ldexp.md#decl-N" class="code_var">N</a>&gt; <a href="ldexp.md">ldexp</a>&lt;<a href="ldexp.md#typeparam-T" class="code_type">T</a>, <a href="ldexp.md#typeparam-E" class="code_type">E</a>, <a href="ldexp.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="ldexp.md#typeparam-T" class="code_type">T</a>, <a href="ldexp.md#decl-N" class="code_var">N</a>&gt; <a href="ldexp.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="ldexp.md#typeparam-E" class="code_type">E</a>, <a href="ldexp.md#decl-N" class="code_var">N</a>&gt; <a href="ldexp.md#decl-exp" class="code_param">exp</a>)
    <span class='code_keyword'>where</span> <a href="ldexp.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="ldexp.md#typeparam-E" class="code_type">E</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int
####  <a id="typeparam-E"></a>E: [\_\_BuiltinIntegerType](../interfaces/0_builtinintegertype-029g/index.md)

## Parameters

####  <a id="decl-x"></a>x  : [T](ldexp.md#typeparam-T)
The significand.

####  <a id="decl-exp"></a>exp  : [T](ldexp.md#typeparam-T)
The exponent.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The significand.

####  <a id="decl-exp"></a>exp  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The exponent.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The significand.

####  <a id="decl-exp"></a>exp  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The exponent.

####  <a id="decl-exp"></a>exp  : [E](ldexp.md#typeparam-E)
The exponent.

####  <a id="decl-exp"></a>exp  : [vector](../types/vector/index.md)\<E, [N](../types/vector/index.md#decl-N)\>
The exponent.


## Return value
The floating-point number constructed from <span class='code'><a href="ldexp.md#decl-x" class="code_param">x</a></span> and <span class='code'><a href="ldexp.md#decl-exp" class="code_param">exp</a></span>.


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




<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      const href = link.getAttribute('href');
      if (href && href.includes('.md')) {
        // This regex will handle .md links with or without fragment identifiers or query parameters
        link.href = link.href.replace(/(.+)\.md(#[^?]*)?(\?.*)?$/, '$1.html$2$3');
      }
    });
  });
}
</script>
