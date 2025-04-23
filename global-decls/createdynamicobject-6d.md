---
layout: stdlib-reference
---

# createDynamicObject

## Description





## Signature 

<pre>
<a href="createdynamicobject-6d.md#typeparam-T" class="code_type">T</a> <a href="createdynamicobject-6d.md">createDynamicObject</a>&lt;<a href="createdynamicobject-6d.md#typeparam-T" class="code_type">T</a>, <a href="createdynamicobject-6d.md#typeparam-U" class="code_type">U</a>&gt;(
    <span class="code_keyword">uint</span> <a href="createdynamicobject-6d.md#decl-typeId" class="code_param">typeId</a>,
    <a href="createdynamicobject-6d.md#typeparam-U" class="code_type">U</a> <a href="createdynamicobject-6d.md#decl-value" class="code_param">value</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T
####  <a id="typeparam-U"></a>U

## Parameters

####  <a id="decl-typeId"></a>typeId  : uint
####  <a id="decl-value"></a>value  : [U](createdynamicobject-6d.md#typeparam-U)


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
