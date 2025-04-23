---
layout: stdlib-reference
---

# determinant

## Description

Compute matrix determinant.



## Signature 

<pre>
<a href="determinant.md#typeparam-T" class="code_type">T</a> <a href="determinant.md">determinant</a>&lt;<a href="determinant.md#typeparam-T" class="code_type">T</a>, <a href="determinant.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="determinant.md#typeparam-T" class="code_type">T</a>, <a href="determinant.md#decl-N" class="code_var">N</a>, <a href="determinant.md#decl-N" class="code_var">N</a>&gt; <a href="determinant.md#decl-m" class="code_param">m</a>)
    <span class='code_keyword'>where</span> <a href="determinant.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-m"></a>m  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [N](../types/matrix/index.md#decl-N)\>
The matrix.


## Return value
The determinant of the matrix.


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
