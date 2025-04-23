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

GetAttributes <../types/hitobject-03/getattributes-03>
GetCurrentTime <../types/hitobject-03/getcurrenttime-03a>
GetGeometryIndex <../types/hitobject-03/getgeometryindex-03b>
GetHitKind <../types/hitobject-03/gethitkind-036>
GetInstanceID <../types/hitobject-03/getinstanceid-03bc>
GetInstanceIndex <../types/hitobject-03/getinstanceindex-03b>
GetObjectRayDirection <../types/hitobject-03/getobjectraydirection-039c>
GetObjectRayOrigin <../types/hitobject-03/getobjectrayorigin-039c>
GetObjectToWorld <../types/hitobject-03/getobjecttoworld-039b>
GetPrimitiveIndex <../types/hitobject-03/getprimitiveindex-03c>
GetRayDesc <../types/hitobject-03/getraydesc-036>
GetShaderRecordBufferHandle <../types/hitobject-03/getshaderrecordbufferhandle-039fl>
GetShaderTableIndex <../types/hitobject-03/getshadertableindex-039e>
GetWorldToObject <../types/hitobject-03/getworldtoobject-038a>
Invoke <../types/hitobject-03/invoke-0>
IsHit <../types/hitobject-03/ishit-02>
IsMiss <../types/hitobject-03/ismiss-02>
IsNop <../types/hitobject-03/isnop-02>
LoadLocalRootTableConstant <../types/hitobject-03/loadlocalroottableconstant-049di>
MakeHit <../types/hitobject-03/makehit-04>
MakeMiss <../types/hitobject-03/makemiss-04>
MakeMotionHit <../types/hitobject-03/makemotionhit-04a>
MakeMotionMiss <../types/hitobject-03/makemotionmiss-04a>
MakeNop <../types/hitobject-03/makenop-04>
TraceMotionRay <../types/hitobject-03/tracemotionray-05b>
TraceRay <../types/hitobject-03/traceray-05>
init <../types/hitobject-03/init>
```
