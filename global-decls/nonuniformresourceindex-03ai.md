---
layout: stdlib-reference
---

# NonUniformResourceIndex

## Description

<span class='code'><a href="nonuniformresourceindex-03ai.md">NonUniformResourceIndex</a></span> function is used to indicate if the resource index is
divergent, and ensure scalarization happens correctly for each divergent lane.




## Signature 

<pre>
<a href="nonuniformresourceindex-03ai.md#typeparam-T" class="code_type">T</a> <a href="nonuniformresourceindex-03ai.md">NonUniformResourceIndex</a>&lt;<a href="nonuniformresourceindex-03ai.md#typeparam-T" class="code_type">T</a>&gt;(<a href="nonuniformresourceindex-03ai.md#typeparam-T" class="code_type">T</a> <a href="nonuniformresourceindex-03ai.md#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="nonuniformresourceindex-03ai.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="nonuniformresourceindex-03ai.md#typeparam-T" class="code_type">T</a> <a href="nonuniformresourceindex-03ai.md">NonUniformResourceIndex</a>&lt;<a href="nonuniformresourceindex-03ai.md#typeparam-T" class="code_type">T</a>&gt;(<a href="nonuniformresourceindex-03ai.md#typeparam-T" class="code_type">T</a> <a href="nonuniformresourceindex-03ai.md#decl-value" class="code_param">value</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index.md)
####  <a id="typeparam-T"></a>T

## Parameters

####  <a id="decl-index"></a>index  : [T](nonuniformresourceindex-03ai.md#typeparam-T)
####  <a id="decl-value"></a>value  : [T](nonuniformresourceindex-03ai.md#typeparam-T)

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

#### spirv
Available in all stages.

Requires capabilities: `SPV_KHR_non_semantic_info`, `SPV_GOOGLE_user_type`, `spvDerivativeControl`, `spvImageQuery`, `spvImageGatherExtended`, `spvSparseResidency`, `spvMinLod`, `spvFragmentFullyCoveredEXT`, `spvShaderNonUniformEXT`.



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
