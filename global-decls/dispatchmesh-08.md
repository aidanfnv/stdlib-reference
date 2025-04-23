---
layout: stdlib-reference
---

# DispatchMesh

## Description

Specify the number of downstream mesh shader thread groups to invoke from an amplification shader,
and provide the values for per-mesh payload parameters.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="dispatchmesh-08.md">DispatchMesh</a>&lt;<a href="dispatchmesh-08.md#typeparam-P" class="code_type">P</a>&gt;(
    <span class="code_keyword">uint</span> <a href="dispatchmesh-08.md#decl-threadGroupCountX" class="code_param">threadGroupCountX</a>,
    <span class="code_keyword">uint</span> <a href="dispatchmesh-08.md#decl-threadGroupCountY" class="code_param">threadGroupCountY</a>,
    <span class="code_keyword">uint</span> <a href="dispatchmesh-08.md#decl-threadGroupCountZ" class="code_param">threadGroupCountZ</a>,
    <a href="dispatchmesh-08.md#typeparam-P" class="code_type">P</a> <a href="dispatchmesh-08.md#decl-meshPayload" class="code_param">meshPayload</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-P"></a>P

## Parameters

####  <a id="decl-threadGroupCountX"></a>threadGroupCountX  : uint
####  <a id="decl-threadGroupCountY"></a>threadGroupCountY  : uint
####  <a id="decl-threadGroupCountZ"></a>threadGroupCountZ  : uint
####  <a id="decl-meshPayload"></a>meshPayload  : [P](dispatchmesh-08.md#typeparam-P)

## Return value
This function doesn't return.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `amplification`, `mesh`.

#### glsl
Available in stages: `amplification`, `mesh`.

#### metal
Available in stages: `amplification`, `mesh`.

#### spirv
Available in stages: `amplification`, `mesh`.

Requires capability: `spvMeshShadingEXT`.



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
