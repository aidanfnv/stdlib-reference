---
layout: stdlib-reference
---

# cross

## Description

Cross product. Returns the cross product of two 3D vectors.



## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="cross.md#typeparam-T" class="code_type">T</a>, 3&gt; <a href="cross.md">cross</a>&lt;<a href="cross.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="cross.md#typeparam-T" class="code_type">T</a>, 3&gt; <a href="cross.md#decl-left" class="code_param">left</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="cross.md#typeparam-T" class="code_type">T</a>, 3&gt; <a href="cross.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="cross.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="cross.md#typeparam-T" class="code_type">T</a>, 3&gt; <a href="cross.md">cross</a>&lt;<a href="cross.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="cross.md#typeparam-T" class="code_type">T</a>, 3&gt; <a href="cross.md#decl-left" class="code_param">left</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="cross.md#typeparam-T" class="code_type">T</a>, 3&gt; <a href="cross.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="cross.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="typeparam-T"></a>T: [\_\_BuiltinIntegerType](../interfaces/0_builtinintegertype-029g/index.md)

## Parameters

####  <a id="decl-left"></a>left  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), 3\>
The first vector.

####  <a id="decl-right"></a>right  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), 3\>
The second vector.


## Return value
The cross product of <span class='code'><a href="cross.md#decl-left" class="code_param">left</a></span> and <span class='code'><a href="cross.md#decl-right" class="code_param">right</a></span>.


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
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
