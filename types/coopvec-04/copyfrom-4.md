---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.copyFrom

## Description

Copy values from another CoopVec instance into this one. The source CoopVec can have a different element type,
in which case appropriate type conversion will be performed.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">CoopVec</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href="copyfrom-4.md">copyFrom</a>&lt;<a href="copyfrom-4.md#typeparam-U" class="code_type">U</a>&gt;(<a href="index.md" class="code_type">CoopVec</a>&lt;<a href="copyfrom-4.md#typeparam-U" class="code_type">U</a>, <a href="index.md#decl-N" class="code_var">N</a>&gt; <a href="copyfrom-4.md#decl-other" class="code_param">other</a>)
    <span class='code_keyword'>where</span> <a href="copyfrom-4.md#typeparam-U" class="code_type">U</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../../interfaces/0_builtinarithmetictype-029j/index.md)

## Parameters

####  <a id="decl-other"></a>other  : [CoopVec](index.md)\<U, [N](index.md#decl-N)\>
The source CoopVec to copy from.


## Availability and Requirements

Defined for the following targets:

#### hlsl
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
