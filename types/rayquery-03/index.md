---
layout: stdlib-reference
---

# struct RayQuery\<rayFlagsGeneric:uint\>

## Description

Note: The treatment of the <span class='code'><a href="index.md" class="code_type">RayQuery</a></span> type in Slang does not
perfectly match its semantics in vanilla HLSL in some corner
cases. Specifically, a <span class='code'><a href="index.md" class="code_type">RayQuery</a></span> in vanilla HLSL is an
opaque handle to mutable storage, and assigning a <span class='code'><a href="index.md" class="code_type">RayQuery</a></span>
or passing one as a parameter will only copy the *handle*,
potentially resulting in aliasing of the underlying mutable
storage.

In contrast, Slang considers a <span class='code'><a href="index.md" class="code_type">RayQuery</a></span> to own its mutable
state, and (because the API does not support cloning of queries),
<span class='code'><a href="index.md" class="code_type">RayQuery</a></span> values are non-copyable (aka "move-only").

The main place where this arises as a consideration is when
passing a <span class='code'><a href="index.md" class="code_type">RayQuery</a></span> down into a function that will perform
mutating operations on it (e.g., <span class='code'><a href="../../global-decls/traceray-05.md">TraceRay</a></span> or <span class='code'><a href="proceed-0.md">Proceed</a></span>):
```
     void myFunc( inout RayQuery<FLAGS> q )
     {
         q.Proceed();
     }
```
In Slang, a parameter like <span class='code'>q</span> above should be declared <span class='code'><span class="code_keyword">inout</span></span>.
HLSL does not care about whether <span class='code'>q</span> is declared <span class='code'><span class="code_keyword">inout</span></span> or not.

cannot use a cap for struct with unequal target support
since it will propegate rules to children.


## Generic Parameters

####  <a id="decl-rayFlagsGeneric"></a>rayFlagsGeneric  : uint = RAY \_FLAG \_NONE

## Methods

* [init](init.md)
* [TraceRayInline](tracerayinline-058.md)
* [Proceed](proceed-0.md)
* [Abort](abort-0.md)
* [CommitNonOpaqueTriangleHit](commitnonopaquetrianglehit-069fn.md)
* [CommitProceduralPrimitiveHit](commitproceduralprimitivehit-06gp.md)
* [CandidateType](candidatetype-09.md)
* [CommittedStatus](committedstatus-09.md)
* [CandidateProceduralPrimitiveNonOpaque](candidateproceduralprimitivenonopaque-09jsv.md)
* [CandidateTriangleRayT](candidatetrianglerayt-09hk.md)
* [CommittedRayT](committedrayt-09c.md)
* [CandidateRayInstanceCustomIndex](candidaterayinstancecustomindex-09ckq.md)
* [CommittedRayInstanceCustomIndex](committedrayinstancecustomindex-09ckq.md)
* [CandidateRayInstanceId](candidaterayinstanceid-09ck.md)
* [CommittedRayInstanceId](committedrayinstanceid-09ck.md)
* [CandidateRayInstanceShaderBindingTableRecordOffset](candidaterayinstanceshaderbindingtablerecordoffset-09ckqx1218.md)
* [CommittedRayInstanceShaderBindingTableRecordOffset](committedrayinstanceshaderbindingtablerecordoffset-09ckqx1218.md)
* [CandidateRayGeometryIndex](candidateraygeometryindex-09ck.md)
* [CommittedRayGeometryIndex](committedraygeometryindex-09ck.md)
* [CandidateRayPrimitiveIndex](candidaterayprimitiveindex-09cl.md)
* [CommittedRayPrimitiveIndex](committedrayprimitiveindex-09cl.md)
* [CandidateRayBarycentrics](candidateraybarycentrics-09c.md)
* [CommittedRayBarycentrics](committedraybarycentrics-09c.md)
* [CandidateRayFrontFace](candidaterayfrontface-09ch.md)
* [CommittedRayFrontFace](committedrayfrontface-09ch.md)
* [CandidateRayObjectRayDirection](candidaterayobjectraydirection-09cil.md)
* [CommittedRayObjectRayDirection](committedrayobjectraydirection-09cil.md)
* [CandidateRayObjectRayOrigin](candidaterayobjectrayorigin-09cil.md)
* [CommittedRayObjectRayOrigin](committedrayobjectrayorigin-09cil.md)
* [CandidateRayObjectToWorld](candidaterayobjecttoworld-09cik.md)
* [CommittedRayObjectToWorld](committedrayobjecttoworld-09cik.md)
* [CandidateRayWorldToObject](candidaterayworldtoobject-09chj.md)
* [CommittedRayWorldToObject](committedrayworldtoobject-09chj.md)
* [CandidateGetIntersectionTriangleVertexPositions](candidategetintersectiontrianglevertexpositions-09cow12.md)
* [CandidateObjectToWorld3x4](candidateobjecttoworld3x4-09fh.md)
* [CandidateObjectToWorld4x3](candidateobjecttoworld4x3-09fh.md)
* [CandidateWorldToObject3x4](candidateworldtoobject3x4-09eg.md)
* [CandidateWorldToObject4x3](candidateworldtoobject4x3-09eg.md)
* [CandidateInstanceIndex](candidateinstanceindex-09h.md)
* [CandidateInstanceID](candidateinstanceid-09hi.md)
* [CandidatePrimitiveIndex](candidateprimitiveindex-09i.md)
* [CandidateGeometryIndex](candidategeometryindex-09h.md)
* [CandidateInstanceContributionToHitGroupIndex](candidateinstancecontributiontohitgroupindex-09htvy13.md)
* [CandidateObjectRayOrigin](candidateobjectrayorigin-09fi.md)
* [CandidateObjectRayDirection](candidateobjectraydirection-09fi.md)
* [CandidateTriangleFrontFace](candidatetrianglefrontface-09hm.md)
* [CandidateTriangleBarycentrics](candidatetrianglebarycentrics-09h.md)
* [CommittedGetIntersectionTriangleVertexPositions](committedgetintersectiontrianglevertexpositions-09cow12.md)
* [CommittedObjectToWorld3x4](committedobjecttoworld3x4-09fh.md)
* [CommittedObjectToWorld4x3](committedobjecttoworld4x3-09fh.md)
* [CommittedWorldToObject3x4](committedworldtoobject3x4-09eg.md)
* [CommittedWorldToObject4x3](committedworldtoobject4x3-09eg.md)
* [CommittedInstanceIndex](committedinstanceindex-09h.md)
* [CommittedInstanceID](committedinstanceid-09hi.md)
* [CommittedPrimitiveIndex](committedprimitiveindex-09i.md)
* [CommittedGeometryIndex](committedgeometryindex-09h.md)
* [CommittedInstanceContributionToHitGroupIndex](committedinstancecontributiontohitgroupindex-09htvy13.md)
* [CommittedObjectRayOrigin](committedobjectrayorigin-09fi.md)
* [CommittedObjectRayDirection](committedobjectraydirection-09fi.md)
* [CommittedTriangleFrontFace](committedtrianglefrontface-09hm.md)
* [CommittedTriangleBarycentrics](committedtrianglebarycentrics-09h.md)
* [RayFlags](rayflags-03.md)
* [WorldRayOrigin](worldrayorigin-058.md)
* [WorldRayDirection](worldraydirection-058.md)
* [RayTMin](raytmin-034.md)


```{toctree}
:titlesonly:
:hidden:

Abort <../types/rayquery-03/abort-0>
CandidateGeometryIndex <../types/rayquery-03/candidategeometryindex-09h>
CandidateGetIntersectionTriangleVertexPositions <../types/rayquery-03/candidategetintersectiontrianglevertexpositions-09cow12>
CandidateInstanceContributionToHitGroupIndex <../types/rayquery-03/candidateinstancecontributiontohitgroupindex-09htvy13>
CandidateInstanceID <../types/rayquery-03/candidateinstanceid-09hi>
CandidateInstanceIndex <../types/rayquery-03/candidateinstanceindex-09h>
CandidateObjectRayDirection <../types/rayquery-03/candidateobjectraydirection-09fi>
CandidateObjectRayOrigin <../types/rayquery-03/candidateobjectrayorigin-09fi>
CandidateObjectToWorld3x4 <../types/rayquery-03/candidateobjecttoworld3x4-09fh>
CandidateObjectToWorld4x3 <../types/rayquery-03/candidateobjecttoworld4x3-09fh>
CandidatePrimitiveIndex <../types/rayquery-03/candidateprimitiveindex-09i>
CandidateProceduralPrimitiveNonOpaque <../types/rayquery-03/candidateproceduralprimitivenonopaque-09jsv>
CandidateRayBarycentrics <../types/rayquery-03/candidateraybarycentrics-09c>
CandidateRayFrontFace <../types/rayquery-03/candidaterayfrontface-09ch>
CandidateRayGeometryIndex <../types/rayquery-03/candidateraygeometryindex-09ck>
CandidateRayInstanceCustomIndex <../types/rayquery-03/candidaterayinstancecustomindex-09ckq>
CandidateRayInstanceId <../types/rayquery-03/candidaterayinstanceid-09ck>
CandidateRayInstanceShaderBindingTableRecordOffset <../types/rayquery-03/candidaterayinstanceshaderbindingtablerecordoffset-09ckqx1218>
CandidateRayObjectRayDirection <../types/rayquery-03/candidaterayobjectraydirection-09cil>
CandidateRayObjectRayOrigin <../types/rayquery-03/candidaterayobjectrayorigin-09cil>
CandidateRayObjectToWorld <../types/rayquery-03/candidaterayobjecttoworld-09cik>
CandidateRayPrimitiveIndex <../types/rayquery-03/candidaterayprimitiveindex-09cl>
CandidateRayWorldToObject <../types/rayquery-03/candidaterayworldtoobject-09chj>
CandidateTriangleBarycentrics <../types/rayquery-03/candidatetrianglebarycentrics-09h>
CandidateTriangleFrontFace <../types/rayquery-03/candidatetrianglefrontface-09hm>
CandidateTriangleRayT <../types/rayquery-03/candidatetrianglerayt-09hk>
CandidateType <../types/rayquery-03/candidatetype-09>
CandidateWorldToObject3x4 <../types/rayquery-03/candidateworldtoobject3x4-09eg>
CandidateWorldToObject4x3 <../types/rayquery-03/candidateworldtoobject4x3-09eg>
CommitNonOpaqueTriangleHit <../types/rayquery-03/commitnonopaquetrianglehit-069fn>
CommitProceduralPrimitiveHit <../types/rayquery-03/commitproceduralprimitivehit-06gp>
CommittedGeometryIndex <../types/rayquery-03/committedgeometryindex-09h>
CommittedGetIntersectionTriangleVertexPositions <../types/rayquery-03/committedgetintersectiontrianglevertexpositions-09cow12>
CommittedInstanceContributionToHitGroupIndex <../types/rayquery-03/committedinstancecontributiontohitgroupindex-09htvy13>
CommittedInstanceID <../types/rayquery-03/committedinstanceid-09hi>
CommittedInstanceIndex <../types/rayquery-03/committedinstanceindex-09h>
CommittedObjectRayDirection <../types/rayquery-03/committedobjectraydirection-09fi>
CommittedObjectRayOrigin <../types/rayquery-03/committedobjectrayorigin-09fi>
CommittedObjectToWorld3x4 <../types/rayquery-03/committedobjecttoworld3x4-09fh>
CommittedObjectToWorld4x3 <../types/rayquery-03/committedobjecttoworld4x3-09fh>
CommittedPrimitiveIndex <../types/rayquery-03/committedprimitiveindex-09i>
CommittedRayBarycentrics <../types/rayquery-03/committedraybarycentrics-09c>
CommittedRayFrontFace <../types/rayquery-03/committedrayfrontface-09ch>
CommittedRayGeometryIndex <../types/rayquery-03/committedraygeometryindex-09ck>
CommittedRayInstanceCustomIndex <../types/rayquery-03/committedrayinstancecustomindex-09ckq>
CommittedRayInstanceId <../types/rayquery-03/committedrayinstanceid-09ck>
CommittedRayInstanceShaderBindingTableRecordOffset <../types/rayquery-03/committedrayinstanceshaderbindingtablerecordoffset-09ckqx1218>
CommittedRayObjectRayDirection <../types/rayquery-03/committedrayobjectraydirection-09cil>
CommittedRayObjectRayOrigin <../types/rayquery-03/committedrayobjectrayorigin-09cil>
CommittedRayObjectToWorld <../types/rayquery-03/committedrayobjecttoworld-09cik>
CommittedRayPrimitiveIndex <../types/rayquery-03/committedrayprimitiveindex-09cl>
CommittedRayT <../types/rayquery-03/committedrayt-09c>
CommittedRayWorldToObject <../types/rayquery-03/committedrayworldtoobject-09chj>
CommittedStatus <../types/rayquery-03/committedstatus-09>
CommittedTriangleBarycentrics <../types/rayquery-03/committedtrianglebarycentrics-09h>
CommittedTriangleFrontFace <../types/rayquery-03/committedtrianglefrontface-09hm>
CommittedWorldToObject3x4 <../types/rayquery-03/committedworldtoobject3x4-09eg>
CommittedWorldToObject4x3 <../types/rayquery-03/committedworldtoobject4x3-09eg>
Proceed <../types/rayquery-03/proceed-0>
RayFlags <../types/rayquery-03/rayflags-03>
RayTMin <../types/rayquery-03/raytmin-034>
TraceRayInline <../types/rayquery-03/tracerayinline-058>
WorldRayDirection <../types/rayquery-03/worldraydirection-058>
WorldRayOrigin <../types/rayquery-03/worldrayorigin-058>
init <../types/rayquery-03/init>
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
