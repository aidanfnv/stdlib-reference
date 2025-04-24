---
layout: stdlib-reference
---

# struct HitObject

## Description

Immutable data type representing a ray hit or a miss. Can be used to invoke hit or miss shading,
or as a key in ReorderThread. Created by one of several methods described below. HitObject
and its related functions are available in raytracing shader types only.


## Methods

* [init](init.html)
* [TraceRay](traceray-05.html)
* [TraceMotionRay](tracemotionray-05b.html)
* [MakeHit](makehit-04.html)
* [MakeMotionHit](makemotionhit-04a.html)
* [MakeMiss](makemiss-04.html)
* [MakeMotionMiss](makemotionmiss-04a.html)
* [MakeNop](makenop-04.html)
* [Invoke](invoke-0.html)
* [IsMiss](ismiss-02.html)
* [IsHit](ishit-02.html)
* [IsNop](isnop-02.html)
* [GetRayDesc](getraydesc-036.html)
* [GetShaderTableIndex](getshadertableindex-039e.html)
* [GetInstanceIndex](getinstanceindex-03b.html)
* [GetInstanceID](getinstanceid-03bc.html)
* [GetGeometryIndex](getgeometryindex-03b.html)
* [GetPrimitiveIndex](getprimitiveindex-03c.html)
* [GetHitKind](gethitkind-036.html)
* [GetWorldToObject](getworldtoobject-038a.html)
* [GetObjectToWorld](getobjecttoworld-039b.html)
* [GetCurrentTime](getcurrenttime-03a.html)
* [GetObjectRayOrigin](getobjectrayorigin-039c.html)
* [GetObjectRayDirection](getobjectraydirection-039c.html)
* [GetShaderRecordBufferHandle](getshaderrecordbufferhandle-039fl.html)
* [GetAttributes](getattributes-03.html)
* [LoadLocalRootTableConstant](loadlocalroottableconstant-049di.html)


```{toctree}
:titlesonly:
:hidden:

GetAttributes <getattributes-03>
GetCurrentTime <getcurrenttime-03a>
GetGeometryIndex <getgeometryindex-03b>
GetHitKind <gethitkind-036>
GetInstanceID <getinstanceid-03bc>
GetInstanceIndex <getinstanceindex-03b>
GetObjectRayDirection <getobjectraydirection-039c>
GetObjectRayOrigin <getobjectrayorigin-039c>
GetObjectToWorld <getobjecttoworld-039b>
GetPrimitiveIndex <getprimitiveindex-03c>
GetRayDesc <getraydesc-036>
GetShaderRecordBufferHandle <getshaderrecordbufferhandle-039fl>
GetShaderTableIndex <getshadertableindex-039e>
GetWorldToObject <getworldtoobject-038a>
Invoke <invoke-0>
IsHit <ishit-02>
IsMiss <ismiss-02>
IsNop <isnop-02>
LoadLocalRootTableConstant <loadlocalroottableconstant-049di>
MakeHit <makehit-04>
MakeMiss <makemiss-04>
MakeMotionHit <makemotionhit-04a>
MakeMotionMiss <makemotionmiss-04a>
MakeNop <makenop-04>
TraceMotionRay <tracemotionray-05b>
TraceRay <traceray-05>
init <init>
```
