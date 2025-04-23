---
layout: stdlib-reference
---

# RaytracingAccelerationStructure\.init

## Description





## Signature 

<pre>
<a href="index.md" class="code_type">RaytracingAccelerationStructure</a>.<a href="init.md">init</a>(uint64_t <a href="init.md#decl-address" class="code_param">address</a>);

<a href="index.md" class="code_type">RaytracingAccelerationStructure</a>.<a href="init.md">init</a>(__DynamicResource&lt;__DynamicResourceKind.General&gt; <a href="init.md#decl-res" class="code_param">res</a>);

<a href="index.md" class="code_type">RaytracingAccelerationStructure</a>.<a href="init.md">init</a>(<a href="../descriptorhandle-0a/index.md" class="code_type">DescriptorHandle</a>&lt;<a href="index.md" class="code_type">RaytracingAccelerationStructure</a>&gt; <a href="init.md#decl-bindless" class="code_param">bindless</a>);

</pre>

## Parameters

####  <a id="decl-address"></a>address  : uint64\_t
####  <a id="decl-res"></a>res  : \_\_DynamicResource\<\_\_DynamicResourceKind\.General\>
####  <a id="decl-bindless"></a>bindless  : [DescriptorHandle](../descriptorhandle-0a/index.md)\<[RaytracingAccelerationStructure](index.md)\>

## Availability and Requirements

Defined for the following targets:

#### glsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvRayTracingKHR`.



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
