---
layout: stdlib-reference
---

# getDescriptorFromHandle

## Description

Declaration of the <span class='code'><a href="getdescriptorfromhandle-3dh.md">getDescriptorFromHandle</a></span> that the user code can provide to customize
how a descriptor handle is converted into a actual descriptor.




## Signature 

<pre>
<a href="getdescriptorfromhandle-3dh.md#typeparam-T" class="code_type">T</a> <a href="getdescriptorfromhandle-3dh.md">getDescriptorFromHandle</a>&lt;<a href="getdescriptorfromhandle-3dh.md#typeparam-T" class="code_type">T</a>&gt;(<a href="../types/descriptorhandle-0a/index.md" class="code_type">DescriptorHandle</a>&lt;<a href="getdescriptorfromhandle-3dh.md#typeparam-T" class="code_type">T</a>&gt; <a href="getdescriptorfromhandle-3dh.md#decl-handleValue" class="code_param">handleValue</a>)
    <span class='code_keyword'>where</span> <a href="getdescriptorfromhandle-3dh.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/iopaquedescriptor-017/index.md" class="code_type">IOpaqueDescriptor</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [IOpaqueDescriptor](../interfaces/iopaquedescriptor-017/index.md)

## Parameters

####  <a id="decl-handleValue"></a>handleValue  : [DescriptorHandle](../types/descriptorhandle-0a/index.md)\<[T](../types/descriptorhandle-0a/index.md#typeparam-T)\>


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
