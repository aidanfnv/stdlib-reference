---
layout: stdlib-reference
---

# struct DescriptorHandle\<T\>

*Conforms to:* [IComparable](../../interfaces/icomparable-01/index.md)

## Description

Represents a bindless handle to a descriptor. A descriptor handle is always an ordinary data type and can be
declared in any memory location.

## Generic Parameters

####  <a id="typeparam-T"></a>T: [IOpaqueDescriptor](../../interfaces/iopaquedescriptor-017/index.md)

## Methods

* [init](init.md)
* [equals](equals.md)
* [lessThan](lessthan-4.md)
* [lessThanOrEquals](lessthanorequals-48a.md)

## Remarks

Opaque descriptor types such as textures(<span class='code'><a href="../texture2d-08.md" class="code_type">Texture2D</a></span> etc.), <span class='code'><a href="../samplerstate-07/index.md" class="code_type">SamplerState</a></span> and buffers (e.g. <span class='code'><a href="../structuredbuffer-0a/index.md" class="code_type">StructuredBuffer</a></span>)
can have undefined size and data representation on many targets. On platforms such as Vulkan and D3D12, descriptors are
communicated to the shader code by calling the host side API to write the descriptor into a descriptor set or table, instead
of directly writing bytes into an ordinary GPU accessible buffer. As a result, oapque handle types cannot be used in places
that refer to a ordinary buffer location, such as as element types of a <span class='code'><a href="../structuredbuffer-0a/index.md" class="code_type">StructuredBuffer</a></span>.
However, a <span class='code'><a href="index.md" class="code_type">DescriptorHandle</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;</span> stores a handle (or address) to the actual descriptor, and is always an ordinary data type
that can be manipulated directly in the shader code. This gives the developer the flexibility to embed and pass around descriptor
parameters throughout the code, to enable cleaner modular designs.
See [User Guide](https://shader-slang.com/slang/user-guide/convenience-features.html#descriptorhandle-for-bindless-descriptor-access)
for more information on how to use <span class='code'><a href="index.md" class="code_type">DescriptorHandle</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;</span> in your code.



```{toctree}
:titlesonly:
:hidden:

equals <../types/descriptorhandle-0a/equals>
init <../types/descriptorhandle-0a/init>
lessThan <../types/descriptorhandle-0a/lessthan-4>
lessThanOrEquals <../types/descriptorhandle-0a/lessthanorequals-48a>
```

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
