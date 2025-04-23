---
layout: stdlib-reference
---

# refract

## Description

Refract incident vector given surface normal and index of refraction.



## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="refract.md#typeparam-T" class="code_type">T</a>, <a href="refract.md#decl-N" class="code_var">N</a>&gt; <a href="refract.md">refract</a>&lt;<a href="refract.md#typeparam-T" class="code_type">T</a>, <a href="refract.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="refract.md#typeparam-T" class="code_type">T</a>, <a href="refract.md#decl-N" class="code_var">N</a>&gt; <a href="refract.md#decl-i" class="code_param">i</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="refract.md#typeparam-T" class="code_type">T</a>, <a href="refract.md#decl-N" class="code_var">N</a>&gt; <a href="refract.md#decl-n" class="code_param">n</a>,
    <a href="refract.md#typeparam-T" class="code_type">T</a> <a href="refract.md#decl-eta" class="code_param">eta</a>)
    <span class='code_keyword'>where</span> <a href="refract.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="refract.md#typeparam-T" class="code_type">T</a> <a href="refract.md">refract</a>&lt;<a href="refract.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="refract.md#typeparam-T" class="code_type">T</a> <a href="refract.md#decl-i" class="code_param">i</a>,
    <a href="refract.md#typeparam-T" class="code_type">T</a> <a href="refract.md#decl-n" class="code_param">n</a>,
    <a href="refract.md#typeparam-T" class="code_type">T</a> <a href="refract.md#decl-eta" class="code_param">eta</a>)
    <span class='code_keyword'>where</span> <a href="refract.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-i"></a>i  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The incident vector.

####  <a id="decl-n"></a>n  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The normal vector.

####  <a id="decl-eta"></a>eta  : [T](refract.md#typeparam-T)
The relative refractive index.

####  <a id="decl-i"></a>i  : [T](refract.md#typeparam-T)
The incident vector.

####  <a id="decl-n"></a>n  : [T](refract.md#typeparam-T)
The normal vector.


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
