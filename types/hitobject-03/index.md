---
layout: stdlib-reference
---

# struct HitObject

## Description

Immutable data type representing a ray hit or a miss. Can be used to invoke hit or miss shading,
or as a key in ReorderThread. Created by one of several methods described below. HitObject
and its related functions are available in raytracing shader types only.


## Methods

* [init](init.md)
* [TraceRay](traceray-05.md)
* [TraceMotionRay](tracemotionray-05b.md)
* [MakeHit](makehit-04.md)
* [MakeMotionHit](makemotionhit-04a.md)
* [MakeMiss](makemiss-04.md)
* [MakeMotionMiss](makemotionmiss-04a.md)
* [MakeNop](makenop-04.md)
* [Invoke](invoke-0.md)
* [IsMiss](ismiss-02.md)
* [IsHit](ishit-02.md)
* [IsNop](isnop-02.md)
* [GetRayDesc](getraydesc-036.md)
* [GetShaderTableIndex](getshadertableindex-039e.md)
* [GetInstanceIndex](getinstanceindex-03b.md)
* [GetInstanceID](getinstanceid-03bc.md)
* [GetGeometryIndex](getgeometryindex-03b.md)
* [GetPrimitiveIndex](getprimitiveindex-03c.md)
* [GetHitKind](gethitkind-036.md)
* [GetWorldToObject](getworldtoobject-038a.md)
* [GetObjectToWorld](getobjecttoworld-039b.md)
* [GetCurrentTime](getcurrenttime-03a.md)
* [GetObjectRayOrigin](getobjectrayorigin-039c.md)
* [GetObjectRayDirection](getobjectraydirection-039c.md)
* [GetShaderRecordBufferHandle](getshaderrecordbufferhandle-039fl.md)
* [GetAttributes](getattributes-03.md)
* [LoadLocalRootTableConstant](loadlocalroottableconstant-049di.md)


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
