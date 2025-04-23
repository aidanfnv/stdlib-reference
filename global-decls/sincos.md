---
layout: stdlib-reference
---

# sincos

## Description

Sine and cosine.
Calculate both the sine and cosine of <span class='code'><a href="sincos.md#decl-x" class="code_param">x</a></span>.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="sincos.md">sincos</a>&lt;<a href="sincos.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="sincos.md#typeparam-T" class="code_type">T</a> <a href="sincos.md#decl-x" class="code_param">x</a>,
    <span class="code_keyword">out</span> <a href="sincos.md#typeparam-T" class="code_type">T</a> <a href="sincos.md#decl-s" class="code_param">s</a>,
    <span class="code_keyword">out</span> <a href="sincos.md#typeparam-T" class="code_type">T</a> <a href="sincos.md#decl-c" class="code_param">c</a>)
    <span class='code_keyword'>where</span> <a href="sincos.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<span class="code_keyword">void</span> <a href="sincos.md">sincos</a>&lt;<a href="sincos.md#typeparam-T" class="code_type">T</a>, <a href="sincos.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="sincos.md#typeparam-T" class="code_type">T</a>, <a href="sincos.md#decl-N" class="code_var">N</a>&gt; <a href="sincos.md#decl-x" class="code_param">x</a>,
    <span class="code_keyword">out</span> <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="sincos.md#typeparam-T" class="code_type">T</a>, <a href="sincos.md#decl-N" class="code_var">N</a>&gt; <a href="sincos.md#decl-s" class="code_param">s</a>,
    <span class="code_keyword">out</span> <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="sincos.md#typeparam-T" class="code_type">T</a>, <a href="sincos.md#decl-N" class="code_var">N</a>&gt; <a href="sincos.md#decl-c" class="code_param">c</a>)
    <span class='code_keyword'>where</span> <a href="sincos.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<span class="code_keyword">void</span> <a href="sincos.md">sincos</a>&lt;<a href="sincos.md#typeparam-T" class="code_type">T</a>, <a href="sincos.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="sincos.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>, <a href="sincos.md#decl-L1" class="code_var">L1</a>:<span class="code_keyword">int</span>, <a href="sincos.md#decl-L2" class="code_var">L2</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="sincos.md#typeparam-T" class="code_type">T</a>, <a href="sincos.md#decl-N" class="code_var">N</a>, <a href="sincos.md#decl-M" class="code_var">M</a>&gt; <a href="sincos.md#decl-x" class="code_param">x</a>,
    <span class="code_keyword">out</span> <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="sincos.md#typeparam-T" class="code_type">T</a>, <a href="sincos.md#decl-N" class="code_var">N</a>, <a href="sincos.md#decl-M" class="code_var">M</a>&gt; <a href="sincos.md#decl-s" class="code_param">s</a>,
    <span class="code_keyword">out</span> <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="sincos.md#typeparam-T" class="code_type">T</a>, <a href="sincos.md#decl-N" class="code_var">N</a>, <a href="sincos.md#decl-M" class="code_var">M</a>&gt; <a href="sincos.md#decl-c" class="code_param">c</a>)
    <span class='code_keyword'>where</span> <a href="sincos.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int
####  <a id="decl-L1"></a>L1  : int
####  <a id="decl-L2"></a>L2  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](sincos.md#typeparam-T)
The angle in radians.

####  <a id="decl-s"></a>s  : [T](sincos.md#typeparam-T)
\[out\] The sine of <span class='code'><a href="sincos.md#decl-x" class="code_param">x</a></span>.

####  <a id="decl-c"></a>c  : [T](sincos.md#typeparam-T)
\[out\] The cosine of <span class='code'><a href="sincos.md#decl-x" class="code_param">x</a></span>.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The angle in radians.

####  <a id="decl-s"></a>s  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
\[out\] The sine of <span class='code'><a href="sincos.md#decl-x" class="code_param">x</a></span>.

####  <a id="decl-c"></a>c  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
\[out\] The cosine of <span class='code'><a href="sincos.md#decl-x" class="code_param">x</a></span>.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The angle in radians.

####  <a id="decl-s"></a>s  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
\[out\] The sine of <span class='code'><a href="sincos.md#decl-x" class="code_param">x</a></span>.

####  <a id="decl-c"></a>c  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
\[out\] The cosine of <span class='code'><a href="sincos.md#decl-x" class="code_param">x</a></span>.


## Return value
void


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
