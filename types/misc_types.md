---
layout: stdlib-reference
---
# Miscelaneous types

This category contains the following declarations:

#### [DefaultDataLayout](defaultdatalayout-07b/index.md)

#### [MemoryOrder](memoryorder-06/index.md)

#### [NativeString](nativestring-06/index.md)

#### [ScalarDataLayout](scalardatalayout-06a/index.md)

#### [SideEffectBehavior](sideeffectbehavior-04a/index.md)

#### [Std140DataLayout](std140datalayout-06a/index.md)

#### [Std430DataLayout](std430datalayout-06a/index.md)

#### [\_\_Shape1D](0_shape1d-028/index.md)

#### [\_\_Shape2D](0_shape2d-028/index.md)

#### [\_\_Shape3D](0_shape3d-028/index.md)

#### [\_\_ShapeBuffer](0_shapebuffer-027/index.md)

#### [\_\_ShapeCube](0_shapecube-027/index.md)

#### [string](string.md)


```{toctree}
:titlesonly:
:hidden:

DefaultDataLayout <../types/defaultdatalayout-07b/index>
MemoryOrder <../types/memoryorder-06/index>
NativeString <../types/nativestring-06/index>
ScalarDataLayout <../types/scalardatalayout-06a/index>
SideEffectBehavior <../types/sideeffectbehavior-04a/index>
Std140DataLayout <../types/std140datalayout-06a/index>
Std430DataLayout <../types/std430datalayout-06a/index>
__Shape1D <../types/0_shape1d-028/index>
__Shape2D <../types/0_shape2d-028/index>
__Shape3D <../types/0_shape3d-028/index>
__ShapeBuffer <../types/0_shapebuffer-027/index>
__ShapeCube <../types/0_shapecube-027/index>
string <../types/string>
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
