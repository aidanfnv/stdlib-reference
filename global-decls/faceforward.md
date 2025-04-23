---
layout: stdlib-reference
---

# faceforward

## Description

Flip vector to face forward, if needed.



## Signature 

<pre>
<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="faceforward.md#typeparam-T" class="code_type">T</a>, <a href="faceforward.md#decl-N" class="code_var">N</a>&gt; <a href="faceforward.md">faceforward</a>&lt;<a href="faceforward.md#typeparam-T" class="code_type">T</a>, <a href="faceforward.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="faceforward.md#typeparam-T" class="code_type">T</a>, <a href="faceforward.md#decl-N" class="code_var">N</a>&gt; <a href="faceforward.md#decl-n" class="code_param">n</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="faceforward.md#typeparam-T" class="code_type">T</a>, <a href="faceforward.md#decl-N" class="code_var">N</a>&gt; <a href="faceforward.md#decl-i" class="code_param">i</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="faceforward.md#typeparam-T" class="code_type">T</a>, <a href="faceforward.md#decl-N" class="code_var">N</a>&gt; <a href="faceforward.md#decl-ng" class="code_param">ng</a>)
    <span class='code_keyword'>where</span> <a href="faceforward.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-n"></a>n  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The vector to orient.

####  <a id="decl-i"></a>i  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The incident vector.

####  <a id="decl-ng"></a>ng  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The geometric normal vector.


## Return value
<span class='code'><a href="faceforward.md#decl-n" class="code_param">n</a></span> if the dot product of <span class='code'><a href="faceforward.md#decl-ng" class="code_param">ng</a></span> and <span class='code'><a href="faceforward.md#decl-i" class="code_param">i</a></span> is less than 0, otherwise <span class='code'>-<a href="faceforward.md#decl-n" class="code_param">n</a></span>.


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
