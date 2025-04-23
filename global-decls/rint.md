---
layout: stdlib-reference
---

# rint

## Description

Round even.



## Signature 

<pre>
<a href="rint.md#typeparam-T" class="code_type">T</a> <a href="rint.md">rint</a>&lt;<a href="rint.md#typeparam-T" class="code_type">T</a>&gt;(<a href="rint.md#typeparam-T" class="code_type">T</a> <a href="rint.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="rint.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="rint.md#typeparam-T" class="code_type">T</a>, <a href="rint.md#decl-N" class="code_var">N</a>&gt; <a href="rint.md">rint</a>&lt;<a href="rint.md#typeparam-T" class="code_type">T</a>, <a href="rint.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="rint.md#typeparam-T" class="code_type">T</a>, <a href="rint.md#decl-N" class="code_var">N</a>&gt; <a href="rint.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="rint.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](rint.md#typeparam-T)
The value to round.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The value to round.


## Return value
The value rounded to the nearest integer, with ties rounded to the nearest even integer.


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
