---
layout: stdlib-reference
---

# SetMeshOutputCounts

## Description

Set the number of output vertices and primitives for a mesh shader invocation.




## Signature 

<pre>
<span class="code_keyword">void</span> <a href="/stdlib-reference/global-decls/setmeshoutputcounts-037d">SetMeshOutputCounts</a>(
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/global-decls/setmeshoutputcounts-037d#decl-vertexCount" class="code_param">vertexCount</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/global-decls/setmeshoutputcounts-037d#decl-primitiveCount" class="code_param">primitiveCount</a>);

</pre>

## Parameters

#### vertexCount  : uint {#decl-vertexCount}
#### primitiveCount  : uint {#decl-primitiveCount}

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


