---
layout: stdlib-reference
---

# asinh

## Description

Arc hyperbolic sine. Returns the arc hyperbolic sine of the specified value.



## Signature 

<pre>
<a href="asinh.md#typeparam-T" class="code_type">T</a> <a href="asinh.md">asinh</a>&lt;<a href="asinh.md#typeparam-T" class="code_type">T</a>&gt;(<a href="asinh.md#typeparam-T" class="code_type">T</a> <a href="asinh.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="asinh.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="asinh.md#typeparam-T" class="code_type">T</a>, <a href="asinh.md#decl-N" class="code_var">N</a>&gt; <a href="asinh.md">asinh</a>&lt;<a href="asinh.md#typeparam-T" class="code_type">T</a>, <a href="asinh.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="asinh.md#typeparam-T" class="code_type">T</a>, <a href="asinh.md#decl-N" class="code_var">N</a>&gt; <a href="asinh.md#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="asinh.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](asinh.md#typeparam-T)
The hyperbolic sine value.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The hyperbolic sine value.


## Return value
The arc hyperbolic sine of the specified value.


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
