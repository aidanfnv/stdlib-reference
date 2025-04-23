---
layout: stdlib-reference
---
# Ray-tracing

This category contains the following declarations:

#### [BuiltInTriangleIntersectionAttributes](builtintriangleintersectionattributes-057fr/index.md)

#### [CANDIDATE\_TYPE](candidate_type-012345678abcd.md)

#### [COMMITTED\_STATUS](committed_status-012345678abcdef.md)

#### [HitObject](hitobject-03/index.md)

#### [RAY\_FLAG](ray_flag-0124567.md)

#### [RayDesc](raydesc-03/index.md)

#### [RayQuery\<rayFlagsGeneric:uint\>](rayquery-03/index.md)

#### [RaytracingAccelerationStructure](raytracingaccelerationstructure-0am/index.md)


```{toctree}
:titlesonly:
:hidden:

BuiltInTriangleIntersectionAttributes <../types/builtintriangleintersectionattributes-057fr/index>
CANDIDATE_TYPE <../types/candidate_type-012345678abcd>
COMMITTED_STATUS <../types/committed_status-012345678abcdef>
HitObject <../types/hitobject-03/index>
RAY_FLAG <../types/ray_flag-0124567>
RayDesc <../types/raydesc-03/index>
RayQuery <../types/rayquery-03/index>
RaytracingAccelerationStructure <../types/raytracingaccelerationstructure-0am/index>
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
