---
layout: stdlib-reference
---

# mad

## Description

Computes multiply-add.



## Signature 

<pre>
/// Requires Capability Set 1:
<a href="mad.md#typeparam-T" class="code_type">T</a> <a href="mad.md">mad</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="mad.md#typeparam-T" class="code_type">T</a> <a href="mad.md#decl-mvalue" class="code_param">mvalue</a>,
    <a href="mad.md#typeparam-T" class="code_type">T</a> <a href="mad.md#decl-avalue" class="code_param">avalue</a>,
    <a href="mad.md#typeparam-T" class="code_type">T</a> <a href="mad.md#decl-bvalue" class="code_param">bvalue</a>)
    <span class='code_keyword'>where</span> <a href="mad.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 1:
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>&gt; <a href="mad.md">mad</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>&gt; <a href="mad.md#decl-mvalue" class="code_param">mvalue</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>&gt; <a href="mad.md#decl-avalue" class="code_param">avalue</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>&gt; <a href="mad.md#decl-bvalue" class="code_param">bvalue</a>)
    <span class='code_keyword'>where</span> <a href="mad.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 1:
<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>, <a href="mad.md#decl-M" class="code_var">M</a>&gt; <a href="mad.md">mad</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mad.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>, <a href="mad.md#decl-M" class="code_var">M</a>&gt; <a href="mad.md#decl-mvalue" class="code_param">mvalue</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>, <a href="mad.md#decl-M" class="code_var">M</a>&gt; <a href="mad.md#decl-avalue" class="code_param">avalue</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>, <a href="mad.md#decl-M" class="code_var">M</a>&gt; <a href="mad.md#decl-bvalue" class="code_param">bvalue</a>)
    <span class='code_keyword'>where</span> <a href="mad.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

/// Requires Capability Set 2:
<a href="mad.md#typeparam-T" class="code_type">T</a> <a href="mad.md">mad</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="mad.md#typeparam-T" class="code_type">T</a> <a href="mad.md#decl-mvalue" class="code_param">mvalue</a>,
    <a href="mad.md#typeparam-T" class="code_type">T</a> <a href="mad.md#decl-avalue" class="code_param">avalue</a>,
    <a href="mad.md#typeparam-T" class="code_type">T</a> <a href="mad.md#decl-bvalue" class="code_param">bvalue</a>)
    <span class='code_keyword'>where</span> <a href="mad.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

/// Requires Capability Set 2:
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>&gt; <a href="mad.md">mad</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>&gt; <a href="mad.md#decl-mvalue" class="code_param">mvalue</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>&gt; <a href="mad.md#decl-avalue" class="code_param">avalue</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>&gt; <a href="mad.md#decl-bvalue" class="code_param">bvalue</a>)
    <span class='code_keyword'>where</span> <a href="mad.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

/// Requires Capability Set 2:
<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>, <a href="mad.md#decl-M" class="code_var">M</a>&gt; <a href="mad.md">mad</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mad.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>, <a href="mad.md#decl-M" class="code_var">M</a>&gt; <a href="mad.md#decl-mvalue" class="code_param">mvalue</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>, <a href="mad.md#decl-M" class="code_var">M</a>&gt; <a href="mad.md#decl-avalue" class="code_param">avalue</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mad.md#typeparam-T" class="code_type">T</a>, <a href="mad.md#decl-N" class="code_var">N</a>, <a href="mad.md#decl-M" class="code_var">M</a>&gt; <a href="mad.md#decl-bvalue" class="code_param">bvalue</a>)
    <span class='code_keyword'>where</span> <a href="mad.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int
####  <a id="typeparam-T"></a>T: [\_\_BuiltinIntegerType](../interfaces/0_builtinintegertype-029g/index.md)

## Parameters

####  <a id="decl-mvalue"></a>mvalue  : [T](mad.md#typeparam-T)
The multiplier.

####  <a id="decl-avalue"></a>avalue  : [T](mad.md#typeparam-T)
The multiplicand.

####  <a id="decl-bvalue"></a>bvalue  : [T](mad.md#typeparam-T)
The addend.

####  <a id="decl-mvalue"></a>mvalue  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The multiplier.

####  <a id="decl-avalue"></a>avalue  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The multiplicand.

####  <a id="decl-bvalue"></a>bvalue  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The addend.

####  <a id="decl-mvalue"></a>mvalue  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The multiplier.

####  <a id="decl-avalue"></a>avalue  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The multiplicand.

####  <a id="decl-bvalue"></a>bvalue  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The addend.


## Return value
The result of <span class='code'><a href="mad.md#decl-mvalue" class="code_param">mvalue</a>*<a href="mad.md#decl-avalue" class="code_param">avalue</a>+<a href="mad.md#decl-bvalue" class="code_param">bvalue</a></span>.


## Availability and Requirements

### Capability Set 1

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


### Capability Set 2

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
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
