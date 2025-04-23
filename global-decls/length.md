---
layout: stdlib-reference
---

# length

## Description

Compute the length of a vector.



## Signature 

<pre>
<a href="length.md#typeparam-T" class="code_type">T</a> <a href="length.md">length</a>&lt;<a href="length.md#typeparam-T" class="code_type">T</a>, <a href="length.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="length.md#typeparam-T" class="code_type">T</a>, <a href="length.md#decl-N" class="code_var">N</a>&gt; <a href="length.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="length.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="length.md#typeparam-T" class="code_type">T</a> <a href="length.md">length</a>&lt;<a href="length.md#typeparam-T" class="code_type">T</a>&gt;(<a href="length.md#typeparam-T" class="code_type">T</a> <a href="length.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="length.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The input vector.

####  <a id="decl-x"></a>x  : [T](length.md#typeparam-T)
The input vector.


## Return value
The length of <span class='code'><a href="length.md#decl-x" class="code_param">x</a></span>.


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
