---
layout: stdlib-reference
---

# nonuniform

## Description





## Signature 

<pre>
<a href="../types/descriptorhandle-0a/index.md" class="code_type">DescriptorHandle</a>&lt;<a href="nonuniform.md#typeparam-T" class="code_type">T</a>&gt; <a href="nonuniform.md">nonuniform</a>&lt;<a href="nonuniform.md#typeparam-T" class="code_type">T</a>&gt;(<a href="../types/descriptorhandle-0a/index.md" class="code_type">DescriptorHandle</a>&lt;<a href="nonuniform.md#typeparam-T" class="code_type">T</a>&gt; <a href="nonuniform.md#decl-ptr" class="code_param">ptr</a>)
    <span class='code_keyword'>where</span> <a href="nonuniform.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/iopaquedescriptor-017/index.md" class="code_type">IOpaqueDescriptor</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [IOpaqueDescriptor](../interfaces/iopaquedescriptor-017/index.md)

## Parameters

####  <a id="decl-ptr"></a>ptr  : [DescriptorHandle](../types/descriptorhandle-0a/index.md)\<[T](../types/descriptorhandle-0a/index.md#typeparam-T)\>


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
