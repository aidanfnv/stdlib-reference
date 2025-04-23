---
layout: stdlib-reference
---

# IFloat\.scale

## Description

Multiplies a value of the conforming type by a floating point scale factor..




## Signature 

<pre>
<a href="index.md" class="code_type">IFloat</a>.<span class="code_keyword">This</span> <a href="index.md" class="code_type">IFloat</a>.<a href="scale.md">scale</a>&lt;<a href="scale.md#typeparam-T" class="code_type">T</a>&gt;(<a href="scale.md#typeparam-T" class="code_type">T</a> <a href="scale.md">scale</a>)
    <span class='code_keyword'>where</span> <a href="scale.md#typeparam-T" class="code_type">T</a> : <a href="../0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../0_builtinfloatingpointtype-029hm/index.md)

## Parameters

####  <a id="decl-scale"></a>scale  : [T](scale.md#typeparam-T)


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
