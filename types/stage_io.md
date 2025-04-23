---
layout: stdlib-reference
---
# Stage IO types

This category contains the following declarations:

#### [InputPatch\<T, N:int\>](inputpatch-05/index.md)

#### [LineStream\<T\>](linestream-04/index.md)

#### [OutputIndices\<T, MAX\_PRIMITIVES:uint\>](outputindices-06/index.md)

#### [OutputPatch\<T, N:int\>](outputpatch-06/index.md)

#### [OutputPrimitives\<T, MAX\_PRIMITIVES:uint\>](outputprimitives-06/index.md)

#### [OutputVertices\<T, MAX\_VERTS:uint\>](outputvertices-06/index.md)

#### [PointStream\<T\>](pointstream-05/index.md)

#### [SubpassInput\<T, isMS:int\>](subpassinput-07.md)

#### [SubpassInputMS\<T, isMS:int\>](subpassinputms-07cd.md)

#### [TextureFootprint\<ND:int\>](texturefootprint-07/index.md)

#### [TextureFootprint2D](texturefootprint2d-07h.md)

#### [TextureFootprint3D](texturefootprint3d-07h.md)

#### [TriangleStream\<T\>](trianglestream-08/index.md)


```{toctree}
:titlesonly:
:hidden:

InputPatch <../types/inputpatch-05/index>
LineStream <../types/linestream-04/index>
OutputIndices <../types/outputindices-06/index>
OutputPatch <../types/outputpatch-06/index>
OutputPrimitives <../types/outputprimitives-06/index>
OutputVertices <../types/outputvertices-06/index>
PointStream <../types/pointstream-05/index>
SubpassInput <../types/subpassinput-07>
SubpassInputMS <../types/subpassinputms-07cd>
TextureFootprint <../types/texturefootprint-07/index>
TextureFootprint2D <../types/texturefootprint2d-07h>
TextureFootprint3D <../types/texturefootprint3d-07h>
TriangleStream <../types/trianglestream-08/index>
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
